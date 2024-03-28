
# Rapport

**Skriv din rapport här!**

_Du kan ta bort all text som finns sedan tidigare_.

## Följande grundsyn gäller dugga-svar:

Ändrade namn på appen via 
```
<string name="app_name">InsertChangedName</string>
```
som befinner sig i strings.xml.

möjliggjorde internet-access, genom att lägga till kodraden
```
 <uses-permission android:name="android.permission.INTERNET"/>
```
i AdroidManifest.xml

Programkod ska se ut som exemplet nedan. Koden måste vara korrekt indenterad då den 
blir lättare att läsa vilket gör det lättare att hitta syntaktiska fel.

Lade till en WebView via kodraden nedan, samt ändrade id till myWebView
```
<WebView
android:id="@+id/myWebView"
android:layout_width="match_parent"
android:layout_height="match_parent"
/>
```
Jag deklarerade classen WebView sedan används för att skapa ett WebView objekt. Denna används för att
exempelvis sätta vilken Url som kommer laddas på WebViewn, samt vilken webView som ska användas.

```
setContentView(R.layout.activity_main);
myWebView = findViewById(R.id.my_WebView);
myWebView.setWebViewClient(new WebViewClient()); // Do not open in Chrome!
myWebView.loadUrl("https://his.se");
WebView myWebView;
```







Bilder läggs i samma mapp som markdown-filen.

![](android.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
