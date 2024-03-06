### Informační systém půjčovny vinylů

#### Součásti systému:

##### Uživatelé:
- **Registrovaní uživatelé:** Osoby, které se zaregistrovaly s uvedením svých osobních údajů, včetně jména, příjmení, e-mailu, telefonního čísla a případně adresy pro účely zasílání. Další údaje, jako jsou způsoby platby, mohou být rovněž bezpečně uloženy.
- **Administrátoři:** Uživatelé se zvýšenými právy, kteří mohou spravovat skladové zásoby, upravovat cenové modely, dohlížet na činnost uživatelů a měnit stav uživatelů a vinylových záznamů.

##### Stavy uživatelů:
- **Aktivní:** Uživatelé, kteří mají dobrou pověst ve službě, nemají žádné zpožděné výpůjčky ani neuhrazené poplatky.
- **Neaktivní:** Uživatelé, kteří mohli deaktivovat svůj účet nebo jim byl administrátorem nastaven neaktivní stav z důvodu dlouhodobé nečinnosti.
- **Omezeni:** Uživatelé, kteří mají zpožděné pronájmy nebo nezaplacené poplatky. Těmto uživatelům je omezeno zadávání nových objednávek, dokud nebude jejich stav vyřešen.

##### Vinylové desky:
- **Atributy dat:** U každé vinylové desky v inventáři budou uvedeny podrobné informace včetně interpreta (interpretů), názvu alba, žánru, roku vydání, stavu (nová, dobrá, přijatelná atd.), ceny za den a aktuálního stavu zásob.
- **Správa skladových zásob:** Při objednávce se automaticky upraví skladové číslo. Není možné pronajmout více kopií, než je na skladě.

#### Zpracování objednávek:
- **Vytvoření objednávky:** Po úspěšné objednávce se vytvoří záznam se všemi relevantními údaji včetně ceny, data zahájení pronájmu, data ukončení pronájmu a původně nulového data vrácení, které bude aktualizováno po vrácení vinylu.
- **Úprava stavu zásob:** Stav zásob vinylu se sníží, aby se zohlednil pronájem.

#### Zpracování opožděných vrácení:
- **Správa opožděných vrácení:** Pokud datum vrácení přesáhne datum ukončení výpůjčky, je uživateli automaticky vystaven poplatek, který je zaznamenán na jeho účtu.
- **Úprava stavu uživatele:** Pokud má uživatel zpožděnou výpůjčku, změní se jeho stav na omezený. Uživatelé s omezeným přístupem nemohou provádět další objednávky, dokud nevrátí opožděnou položku a neuhradí všechny dlužné poplatky.
- **Záznam o poplatku:** Pro každou opožděnou výpůjčku je vytvořen záznam o poplatku, který určuje dlužnou částku na základě počtu dnů opožděné výpůjčky a denní ceny výpůjčky.

#### Další možné funkce:
- **Dynamické ceny:** Zvažte zavedení dynamických cen na základě poptávky, vzácnosti vinylu a případně stavu. Mohlo by se jednat o speciální ceny pro velmi žádaná alba nebo slevy pro vinyly, o které je menší zájem.

Translated with www.DeepL.com/Translator (free version)
