
<h1>About</h1>

<b>Dark and light theme for Home Assistant</b> using CSS, SVG and awesome <a href="https://github.com/thomasloven/lovelace-card-mod">Card-mod</a> from Thomas Lovén

![B   W](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/058d1dde-a932-4b28-81a4-61eccd8886c6)

![dark-main](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/5e753fad-43ba-4f17-9c52-ce8ac6e43185)
![darky](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/df247a86-2fcd-4acf-8599-64f0e69186f0)

![light-main](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/2fec465a-5622-470b-b730-8564f7ad7637)
![light](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/b4feddc5-bbea-407a-8b84-f1e8d7c408ab)



<h1>Installation</h1>

- Copy the 4 directories (dark/light/titles/transparent) in /themes/ Home Assistant folder
- Restart Home Assistant
- Choose "Dark" or "Light" theme (do not use base themes)

<h1>How to use</h1>

Choose "Dark" theme will automatically toggle all cards in dark mode

Choose "Light" theme will automatically toggle all cards in light mode

Now you can use two more themes :

<h2>Transparent theme</h2>

<i>(for pictures without border or background)</i>

Select "Transparent" theme. Card toogles transparent :

![image](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/01b7fa32-2ff1-42b6-a1e2-a07fe904d2c1)

![image](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/71e4538d-6b7b-42d7-b033-e7ce04abd13b)

<h2>Title theme</h2>

Use <b>markdown card</b>, select "Title" theme, and type :

<pre>## &lt;b&gt;YOU TITLE HERE&lt;/b&gt;</pre>

Card toogles transparent and uses special large fonts and CSS Effects

![image](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/9837d09f-002b-4ae9-aba0-39b252c650c7)

![image](https://github.com/Krakoukas73/ha-dark-light/assets/54374596/708c1cfa-9573-4367-81f9-85872954195a)

<h1>Troubleshooting / Work in progress</h1>

- Strange glitches sometimes
- TTF Fonts are not included (Roboto, Bebas Neue). You should add your own fonts in Home Assistant
- Cancel glow/animate/shadow CSS effects (consuming too much CPU even with modern devices)

![glow](https://github.com/Krakoukas73/home-assistant-dark-light/assets/54374596/ddba224d-51ed-4ca6-96d8-017dc35e6ce1)

