Uzdevumi MarkDown
Grūtībā Level 0.

# 1. Uzdevums: Izveidojiet virsrakstu.

**2. Uzdevums: Izveidojiet uzsvērto tekstu (trekns teksts).**

3. Uzdevums: 
- Izveidojiet sadaļu 
- ar sarakstu (punkti).

4. Uzdevums: 

~
1. Izveidojiet 
2. numurētu 
3. sarakstu.

~

5. Uzdevums: Ievietojiet attēlu (lokālu un no arēja Web resursa).

Local: ![image](/Users/Laura/Desktop/Isolated.png)


Web:
![Tux, the Linux mascot](https://mdg.imgix.net/assets/images/tux.png?auto=format&fit=clip&q=40&w=100)

6. Uzdevums: Izveidojiet hiperlinku to [basic syntax](https://www.markdownguide.org/basic-syntax/#line-breaks)

7. Uzdevums: Izveidojiet tabulu ar vairākām kolonnām.

| Column 1| Column 2| Column 3|
| ------- |:-------:| -------:|
| 1       | 1       | 1       |
| 2       | 2       | 2       |
| 3       | 3       | 3       |


8. Uzdevums: Ievietojiet koda fragmentu. Jebkurā valoda.

public void eightComponents() {
        WebDriver driver = new ChromeDriver();
        driver.get("https://www.selenium.dev/selenium/web/web-form.html");
}


> 9. Uzdevums: Izveidojiet citātu.


10.  Uzdevums: Izveidojiet horizontālu līniju.

___

Uzdevumi MarkDown
Grūtībā Level 1.

1. Uzdevums: Izveidojiet numurētu sarakstu ar iekļautiem apakšpunktiem.

1. viens
    - viens
2. divi
   - divi
3. tris
   - tris

2. Uzdevums: Izveidot piezīmi, izmantojot bloķētu citātu formatējumu.

> write you note here please

 
3. Uzdevums: Izveidojiet saites uz failiem, kas atrodas vietējā datorā.

[my link](file\C:\Users\Laura\Desktop\cat.jpg)


4. Uzdevums: Ievietojiet koda bloku ar norādi uz programmatūras valodu – python un java.


    public void eightComponents() {
        WebDriver driver = new ChromeDriver();
        driver.get("https://www.selenium.dev/selenium/web/web-form.html");

        String title = driver.getTitle();
        assertEquals("Web form", title);

        driver.manage().timeouts().implicitlyWait(Duration.ofMillis(500));

        WebElement textBox = driver.findElement(By.name("my-text"));
        WebElement submitButton = driver.findElement(By.cssSelector("button"));

        textBox.sendKeys("Selenium");
        submitButton.click();

        WebElement message = driver.findElement(By.id("message"));
        String value = message.getText();
        assertEquals("Received!", value);

        driver.quit();
    }


5. Uzdevums: Uzrakstiet ķīmisko formulu (Etānos) C2H6O izmantojot attēlojumu līdzīgi ka Word redaktora strādā funkcija subscript subscript.

C<sub>2</sub>H<sub>6</sub>O

6. Uzdevums: Izveidojiet aizvērtu tabulu ar centrētiem tekstiem.

| Syntax      | Description |
| :---------: | :---------: |
| Header      | Title       |
| Paragraph   | Text        |

7. Uzdevums: Ievietojiet Task List/Checkbox, sekojošam sarakstam 

- [x] Popular Databases
- [ ] Oracle
- [x] MySQL
- [ ] Microsoft SQL Server
- [x] PostgreSQL
- [ ] Redis


8. Izvēdījiet stāstu/instrukciju: Izveidojiet īsu stāstu vai instrukciju, izmantojot Markdown, un lietojiet attēlus, lai vizualizētu notikumus/soļus. Vienā sarakstā aprakstiet dažas notikuma detaļas, un katram notikumam pievienojiet attēlu ar saiti, lai to redzētu.


9. Izveidojiet mājaslapu: Izveidojiet vienkāršu HTML lapu, izmantojot Markdown tikai ar saitēm un attēliem. Izmantojiet Markdown, lai izveidotu lapas virsrakstu, definetu saites uz citām lapām un ievietotu attēlus.
