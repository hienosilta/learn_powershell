# Kom igång med PowerShell 
– Grundläggande Guider
## 1. Vad är PowerShell? 
PowerShell är ett kraftfullt skriptverktyg och kommandoradsmiljö, främst för Windows men finns även för Linux och macOS via PowerShell Core. Med PowerShell kan du automatisera administration, hantera filer, och arbeta med systeminställningar. 

## 2. Installation 
### Windows PowerShell är förinstallerat på de flesta Windows-versioner. 
Du kan kontrollera versionen genom att köra: ```powershell $PSVersionTable.PSVersion ``` För den senaste versionen, [ladda ner PowerShell från Microsofts officiella hemsida](https://docs.microsoft.com/powershell/).

### Linux/macOS Installera PowerShell via terminalen: 
```bash # Linux (Ubuntu-exempel) sudo apt-get install -y powershell # macOS med Homebrew brew install --cask powershell ``` 

## 3. Starta PowerShell - 
**Windows:
** Sök efter "PowerShell" i Startmenyn och öppna. 

- **Linux/macOS:
- ** Skriv `pwsh` i din terminal. 

## 4. Din första PowerShell
-kommandon 
Prova dessa enkla kommandon i PowerShell-terminalen: ```
powershell Get-Process 
* Lista alla aktiva processer Get-ChildItem
* Visa filer i aktuell katalog Get-Help Get-Process
* Visa hjälp för ett kommando ``` 

```## 5. Skriva och köra skript 
Spara dina kommandon i en fil med ändelsen `.ps1`, exempelvis `mittskript.ps1`. Kör skriptet så här: ```

powershell .\mittskript.ps1 ``` 

**Obs:**
Du kan behöva ändra exekveringspolicy. Kör som administratör: 

powershell Set-ExecutionPolicy RemoteSigned ``` 

## 6. Vidare läsning
- [Microsoft PowerShell Documentation](https://learn.microsoft.com/powershell/)
- [PowerShell Gallery](https://www.powershellgallery.com/)
- [PowerShell på GitHub](https://github.com/powershell/powershell)  ---

 Vill du ha mer avancerade guider,
 * exempel på skript,
 * eller tips på vanliga användningsområden?
Säg gärna till!
