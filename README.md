# PVA2 - Programování a vývoj aplikací
## Cvičení 20: Git Úvod

### 1. Založení účtu a seznámení s GitHubem
1. Otevřete stránku [https://github.com](https://github.com).  
2. Založte si nový účet (Sign up) – použijte školní e-mail.  
3. Přihlaste se a prozkoumejte uživatelské rozhraní:  
   - **Profile** (váš účet)  
   - **Repositories** (seznam projektů)  
   - **Settings** (nastavení účtu)  
4. Upravte svůj profil:  
   - Přidejte profilovou fotku.  
   - Doplňte krátký popis („student PVA2“ apod.).

### 2. Vytvoření prvního repozitáře
1. Klikněte na **New repository**.  
2. Vyplňte název: `muj-prvni-projekt`.  
3. Zaškrtněte možnost **Add a README file**.  
4. Klikněte na **Create repository**.  
5. Otevřete soubor `README.md` a upravte ho (např. přidejte větu „Toto je můj první projekt“).  
6. Změnu uložte pomocí **Commit changes**.

### 3. Klonování repozitáře a práce lokálně v PyCharmu
1. Otevřete **PyCharm**.  
2. V horním menu klikněte na **Git → Clone...** (nebo na úvodní obrazovce tlačítko **Get from VCS**).  
3. Do pole **URL** vložte adresu repozitáře z GitHubu  
   *(najdete ji na stránce repozitáře pod tlačítkem **Code → HTTPS**)*.  
4. Vyberte složku, kam se má projekt uložit, a potvrďte tlačítkem **Clone**.  
5. PyCharm stáhne repozitář a rovnou jej otevře jako projekt.  

#### Přidání nového souboru
6. V levém panelu (Project) klikněte pravým tlačítkem na projektovou složku.  
7. Zvolte **New → File** a vytvořte soubor `aboutme.md`.  
8. Do souboru napište krátký text o sobě a uložte.  

#### Commit a Push v PyCharmu
9. Vpravo dole klikněte na **Commit** (ikona zeleného fajfky) nebo použijte zkratku **Ctrl+K** (Windows) / **Cmd+K** (Mac).  
10. Zaškrtněte změněný soubor `aboutme.md`, napište zprávu commitu (např. *„Přidán soubor aboutme.md“*) a potvrďte tlačítkem **Commit and Push**.  
11. Pokud zvolíte pouze **Commit**, je potřeba ještě provést **Git → Push**.  
12. Ověřte na GitHubu, že se soubor `aboutme.md` objevil v repozitáři.  
