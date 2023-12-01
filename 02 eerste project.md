
## Json...

Json is leuk maar vaak komt data uit een database

- open een terminal in je `01 start`
    - type `dotnet add package Microsoft.Data.Sqlite`
    - type `dotnet add package Microsoft.EntityFrameworkCore`
    > hier halen we een code library van het internet en koppelen we die aan ons project


///Microsoft.EntityFrameworkCore.SqlServer
> [https://learn.microsoft.com/en-us/dotnet/standard/data/sqlite/?tabs=netcore-cli](https://learn.microsoft.com/en-us/dotnet/standard/data/sqlite/?tabs=netcore-cli)
- maak een repository:
    - `M2flex_ASP`
- clone die naar je PC

- maak in die `M2flex_ASP`  een nieuwe directory:
    - `01 start`
- maak een `.gitignore` file
    - zet daar het volgende in:
    ```
        **bin
        **obj
        **.vs
        **packages
        **/csproj.user
    ```
> !!! Let op dat er geen spaties en tabs voor de ** staan

## eerste project

.net heeft veel verschillende project types, wij gebruiken nu even de `MVC` variant

- maak een nieuwe directory:
    - `01 start`
    - `screenshots`
- open je terminal/cmd
    - ga naar je `01 start` directory
    - type `dotnet new mvc`
    > ![](img/newproject.PNG)


## openen:

- open de directory `01 start` in visual studio code:
    > ![](img/macvisual.PNG)

## draaien

- ga naar je `01 start` directory
- in je terminal type :
    - `dotnet build`
    > ![](img/build.PNG)
    - als er geen errors zijn:
        - type
            - `dotnet run`
            > ![](img/run.PNG)

- open je browser en ga naar het adres wat je in je terminal ziet
    > - bij mij is dat `http://localhost:5272/`
    > - Bij jou kan dat `ANDERS` zijn

- je krijg nu de site:
    > ![](img/site.PNG)


#### WINDOWS

- heb je windows? dan mag je vanaf nu visual studio gebruiken:
> dat ontwikkeld sneller
[100_EXTRA_Windows.md](./100_EXTRA_Windows.md)

## Klaar?

- git add .
- git status
    - staan de `bin` en `obj` er tussen?
        - dan is je `.gitignore` niet goed
            - `fix` dat!
- commit naar je repo voor dit vak
