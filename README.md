
# Fork

## Co je Fork?
Fork je proces, při kterém se vytvoří kopie existujícího projektu, což umožňuje jeho další samostatný vývoj, aniž by se zasahovalo do původní verze. V prostředí verzovacích systémů, jako je Git, se používá pro práci na nových funkcích, opravách chyb nebo experimentování s kódem, aniž by se ovlivnila hlavní větev projektu. Fork poskytuje vývojářům svobodu testovat a vylepšovat projekt podle svých představ. V tomto návodu si ukážeme, jak si Fork nainstalovat a začít s ním pracovat.

## Instalace a nastavení Fork

Fork lze stáhnout z oficiální webové stránky [zde](https://git-fork.com/). Stačí vybrat verzi pro váš operační systém, buď pro **Windows**, nebo **macOS**.

### Po stažení:
1. Spusťte instalační soubor a postupujte podle pokynů.
2. Po dokončení instalace spusťte aplikaci a zadejte své přihlašovací údaje z GitHubu:
   - **1. Přezdívku** (Username)
   - **2. E-mailovou adresu**
   - **3. Cestu pro ukládání souborů** (kam chcete ukládat své projekty)

   ![přihlášení fork](https://github.com/user-attachments/assets/1b7b3fe8-94b4-42ab-bf38-6ccabfbcede8)

3. Klikněte na tlačítko `Finish` a počkejte, až se všechna nastavení načtou.

## Přidání GitHub účtu

Aby bylo možné využívat Fork naplno, je potřeba přidat svůj GitHub účet:

1. Otevřete nabídku `File` a vyberte možnost `Accounts...`.

   ![přidání gtihab učtu 1](https://github.com/user-attachments/assets/08665e37-b6c4-41bf-90eb-54216d56df22)


2. V levém dolním rohu klikněte na znaménko `+`, čímž se otevře okno pro přidání nového účtu.
3. Vyberte možnost `GitHub`, zadejte své GitHub přihlašovací údaje a klikněte na `Sign in`.
   - **Poznámka**: Ujistěte se, že jste ve webovém prohlížeči přihlášeni ke svému GitHub účtu.

   ![Přiradní učut githab 2](https://github.com/user-attachments/assets/fb0b3c3c-3417-4781-ba45-4ebb5a4c4395)


4. Otevře se nové okno, kde potvrdíte propojení svého GitHub účtu s Fork. Poté budete muset zadat své GitHub heslo. Vypadá takto:
   
   ![Snímek obrazovky 2024-09-08 175734](https://github.com/user-attachments/assets/3cbb9b56-7c88-46c3-beb3-795699a6b56c)



6. Nakonec klikněte na `Sign in` a váš účet bude připojen.

## Klonování repozitáře a ukládání změn

Jakmile máte připojený GitHub účet, můžete začít klonovat repozitáře (projekty):

1. V hlavní nabídce klikněte na `File` a zvolte `Clone...`.

   ![klonování 1](https://github.com/user-attachments/assets/8d7e97dc-ef53-45fe-b94f-271cf96a25e1)


2. Otevře se nové okno, kde zadáte URL adresu repozitáře, který chcete klonovat, a název projektu. Poté klikněte na `Clone`.

   ![kolnování 2](https://github.com/user-attachments/assets/b0d1f3e7-0f36-4090-ba5c-f2c23b6e42eb)


3. **Kde najít URL adresu repozitáře?**  
   Otevřete si projekt na GitHubu, který chcete klonovat, a klikněte na tlačítko `<> Code`. Poté zkopírujte URL adresu.

   ![adresa](https://github.com/user-attachments/assets/99467923-cb27-47f7-b692-46c4f294236a)


4. Po klonování můžete repozitář otevřít ve svém oblíbeném editoru, například ve **Visual Studio Code**.

   ![otvíraní](https://github.com/user-attachments/assets/7a7ffce4-3e65-45f2-afb2-321b1e46a290)

### Ukládání změn (Commit a Push)

Pokud provedete nějaké změny v projektu, Fork vám je zobrazí v sekci `Local Changes`.

   ![z1](https://github.com/user-attachments/assets/cc3b5e17-2e4e-4efc-b917-e8dc5511c4ad)


Pro uložení změn na GitHub (commiting):

1. V sekci `Local Changes` vyberte soubory, které chcete commitnout, a klikněte na tlačítko `Stage`.
2. Do spodního řádku napište název commitu (např. "Oprava chyby" nebo "Přidání nové funkce") a přidejte volitelný popis změn.
3. Klikněte na `Commit`.

   ![z2](https://github.com/user-attachments/assets/542c17f5-faa1-401a-a4a5-901871d02747)


Nyní zbývá už jen nahrát změny na GitHub:

1. Klikněte na tlačítko `Push` v horní části aplikace.
2. Vaše změny jsou nyní na GitHubu!
  
   ![z3](https://github.com/user-attachments/assets/a4bd6eae-d8ce-40a3-a460-8cade85a36f2)





