Poznámky.

Typy proměnných
- string - pro slova, fráze nebo jakákoli alfanumerická data pro prezentaci, ne výpočet
- char - pro jeden alfanumerický znak
- int - pro celé číslo
- decimal - pro číslo se zlomkovou komponentou
- bool - true/false - pro hodnotu


Proměnné - Definice
- Proměnné jsou dočasné hodnoty, které ukládáte do paměti počítače.
- Proměnnou musíte napřed deklarovat, abyste ji mohli použít.
- Pokud chcete deklarovat proměnnou, nejprve vyberte datový typ, který dopovídá druhu uložených dat, a pak proměnnou pojmenujte. Dodržujte při tom uvedená pravidla.

Práce s proměnnými
- Před načtením (získání) hodnoty z proměnné musíte přiřadit (nastavit) hodnotu proměnné.
- Proměnnou můžete inicializovat přiřazením hodnoty proměnné v okamžiku deklarace.
- Zadání probíhá zprava doleva.
Jako operátor přiřazení použijete jeden znak rovná se.
- Pokud chcete načíst hodnotu z proměnné, použijte pouze název proměnné.

Implicitní proměnná - (var)
- Klíčové slovo var říká kompilátoru, aby datový typ proměnné odvodil na základě hodnoty, do které je inicializovaný.
- Při čtení kódu jiných lidí se pravděpodobně zobrazí var klíčové slovo. Pokud je to ale možné, měli byste datový typ použít.

Formátování textu v řetězcích pomocí UNICODE
- Pokud potřebujete do řetězce literálu vložit speciální znak, jako je tabulátor \t, nový řádek \n nebo dvojité uvozovky \", použijte řídicí sekvence znaků.
- Pokud potřebujete použít zpětné lomítko v jakékoli jiné situaci, použijte jeho řídicí znak \\.
- Direktiva @ slouží k vytvoření doslovného řetězcového literálu, který uchovává veškeré formátování prázdných znaků a zpětné lomítko v řetězci.
- Pokud chcete v řetězci vyjádřit znaky Unicode (UTF-16), použijte řídicí znak \u a příslušný čtyřmístný kód.
- Znaky Unicode se nemusí správně tisknout v závislosti na aplikaci.

Interpolace řetězců

EXAMPLES
- int version = 11;
string updateText = "Update to Windows";
string message = $"{updateText} {version}";
Console.WriteLine(message);
- string firstName = "Bob";
string message = $"Hello {firstName}!";
Console.WriteLine(message);
Dolar = interpolace, Zavináč = Dají se použít i / -> třeba string projectName = "First-Project";  Console.WriteLine($@"C:\Output\{projectName}\Data");

