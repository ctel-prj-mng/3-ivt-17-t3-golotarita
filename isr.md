### 3.1. Организация и проведение юзабилити-тестирования сайта интернет-магазина и создание отчета о его результатах (в виде презентации или текстового документа)

https://docs.google.com/document/d/13ZBLtBshuCr_7Sx8rnl0I6iR01MHmkF2Zu_7Tgo8pIU/edit?usp=sharing

### 3.2. Проведение юзабилити-тестирования с использованием шкалы "System Usability Scale". Написание отчета по результатам тестирования. 
Тестирование asos.com
* Я хотел бы постоянно использовать эту систему. - 4
* Я считаю систему излишне сложной. - 1
* Я полагаю, что система проста в использовании. - 4
* Мне понадобится помощь технического специалиста, чтобы использовать эту систему. - 1
* Функции в этой системе интегрированы качественно. - 3
* В этой системе слишком много непоследовательности. - 1
* Большинство людей научатся использовать эту систему очень быстро. - 5
* Я считаю систему очень неудобной в использовании. - 2
* Я чувствую себя очень уверенно, используя систему. - 4
* Мне нужно узнать много новой информации, прежде чем я смогу начать работать с этой системой. - 1

Из оценки для каждого из нечетных вопросов вычтите 1 балл. Для каждого из четных вопросов вычтите его значение из 5. Возьмите полученные значения и сложите в общий балл. Затем умножьте это число на 2.5. Полученный результат является процентом удобства использования сайта (оценка максимальной удобности, соответственно, равна 100).

Полученный результат: 85
80.3 или выше. Люди любят ваш сайт и готовы рекомендовать его своим друзьям.

### 3.3. Создание набора модульных (unit) тестов с использованием языка высокого уровня для предложенного преподавателем программного продукта и оформление по результатам тестирования отчета в репозитории с использованием разметки Markdown.

	public void testSum() {
		Calculator calculator = new Calculator();
		int result = calculator.sum(2, 2);
		if (result != 4) {   // if 2 + 2 != 4
			Assert.fail();
		}
	
	public void testMinus() {
		Calculator calculator = new Calculator();
		Assert.assertEquals(0, calculator.minus(2, 2));
	}
  
	public void testDivide() {
		Calculator calculator = new Calculator();
		Assert.assertEquals(2, calculator.divide(6, 3));
	}

### 3.4.  Анализ работы программного продукта (веб-приложения) и создание схемы с последовательностью операций выполняемых ПО на предмет рефакторинга кода и реинжиниринга самого приложения и оформление по результатам отчета в репозитории с использованием разметки Markdown.

