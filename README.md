Aby vám appka šlapala, nainstalujte si npm balíčky:
- Bootstrap - npm i bootstrap@5.3.2 - a pak mrkněte na import v src/index.js, přidejte si jej takto, jinak vám bs nepojede
- axios - npm i axios

Deployment
- deployment je na stránce https://veetektest.g6.cz/projects/weather-app/index.html
- je nastaveno, aby se co dvě minuty aktualizovala data z API - projeví se i na výpisu dané lokality, pokud se mezitím data změnila
- čas poslední aktualizace je vypsán pod výběrem lokality
- poznámka ke kódu - je to narychlo spíchnuté ukázkové řešení, jak by mohl FE k appce vypadat, mám tam určitě chyby a dozajista by se dalo udělat spanilejší a propracovanější řešení, leč smyslem bylo ukázat, jakým směrem je možno se vydat v konkrétním případě... v tomto případě s použitím axios balíčku
