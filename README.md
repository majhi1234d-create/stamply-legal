# Stamply — public legal pages

Public privacy policy, terms of use and third-party licence notices for Stamply, published by Digital Company, s.r.o. Contact: digitalcompanysro@gmail.com.

Languages: Czech, English, German, Polish, Russian and Ukrainian. The document text is unchanged from the Android app’s 0.8.6 legal package dated 4 November 2026. This repository contains only the public website files.

- [Privacy policy](privacy.html) · [České zásady soukromí](cs-privacy.html)
- [Terms of use](terms.html) · [České podmínky](cs-terms.html)
- [Third-party licences and map credits](licenses.html)

## Zveřejnění na GitHub Pages

1. Přihlaste se na GitHub a vytvořte nový repozitář s názvem `stamply-legal`, viditelnost **Public**.
2. Rozbalte dodaný ZIP. Do kořene repozitáře nahrajte jeho obsah: HTML, složku `licenses`, tento README a soubor `.nojekyll`. Nenahrávejte samotný ZIP jako jediný soubor.
3. Přes **Add file → Upload files** nahrajte soubory a celou složku `licenses`, zachovejte její název. Potvrďte změny do větve `main`.
4. V repozitáři otevřete **Settings → Pages**.
5. V **Build and deployment → Source** vyberte **Deploy from a branch**.
6. Vyberte větev **main** a složku **/(root)**, poté **Save**.
7. Vyčkejte na dokončení publikace. Skutečnou adresu zobrazí GitHub v nastavení Pages. Pro Play Console použijte zveřejněnou stránku `privacy.html`, nikoliv odkaz na soubor ve webovém rozhraní repozitáře.
8. Otevřete skutečnou adresu v anonymním okně bez přihlášení; zkontrolujte text, přepínání jazyků i odkazy na podmínky a licence. Potom vložte URL zásad do Google Play Console.

Příklad struktury adresy (šablona, nikoli již zveřejněná URL):
`https://UZIVATEL.github.io/stamply-legal/privacy.html`

Publikování na GitHub ani aktivace GitHub Pages nebyly vytvořením tohoto balíčku provedeny. Konečnou URL je nutné ověřit až po nasazení.

## Údržba

Upravujte odpovídající jazykové verze společně; při podstatné změně obsahu upravte i datum. Právní texty v aplikaci musí odpovídat jejímu skutečnému chování. Obsah neobsahuje vlastní měřicí skripty, formuláře ani externí fonty. Hostitel může vést provozní logy podle svých pravidel.

Původní oznámení třetích stran a jejich licence jsou zachované ve složce `licenses` a na stránkách `*-licenses.html`. Tímto repozitářem se neuděluje licence ke kódu aplikace Stamply.

Oficiální postup: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
