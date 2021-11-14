---
title: How to write markdown and demo of some bugs
---
# Header
## Header
### Header
#### Header
##### Header
###### Header

#tag 
# Header
#tag 
## Header
#tag 
### Header
#tag 
#### Header
#tag 
##### Header
#tag 
###### Header
#tag 

Underlined Head
---
#tag 

Double Underlined Head
=
#tag

Normal
*Italics* (\*)
**Bold** (\*\*)

---
_Italics_ (\_)
__Bold__ (\_\_)
%% Comment %%
~~Striked~~
==Highlighted==
> Blockqoute

Tasks
- [ ] Task list unchecked.
- [x] Task list checked.


List Unordered (+)
+ List item
+ List item
+ List item
	+ Sub list item
	+ Sub list item

List Unordered (-)
- List item
- List item
- List item
	- Sub list item
	- Sub list item

List Ordered		
1. List item
	1. Sub list item
	2. Sub list item
		1. Sub sub list item
		2. Sub sub list item

List Unordered (\*)
* List item
* List item
* List item
	* Sub list item
	* Sub list item

[[WikiLink Page not created]]
[[WikiLink Page created]]
[Link to website](http://www.site.cm)

Inline Math
[$e^{2i\pi} = 1$] 

Math Block
$$\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc$$

Code
`inline`

Code block
```css
.selector {
property: value;
}
```
Image
[[Some image.png]]

Embeded Image
![[Some image.jpg]]

Embeded Audio
![[Some audio.mp3]]
Embeded Video
![[Some video.mp4]]

Embeded Note
![[Some note]]

This is a postponed footnote reference.[^1]
This is inline footnote reference.^[this is the inline note]

[^1]: this is the postponed note.

| Header | Header |
|-|-|
| Stub | Cell |	

Embeded Site (iframe tag)
<iframe href=example.com>
  
This is how Splash screen would look, if it loaded our custom css
  #tag
<html><head>
    <meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
    <title>Obsidian</title>
	<link href="app.css" type="text/css" rel="stylesheet">
</head>
<body class="theme-dark starter is-frameless" style="padding-top: 24px;"><div class="titlebar" style="height: 24px; padding-top: 2px;"><div class="titlebar-inner"><div class="titlebar-left"></div><div class="titlebar-text">Obsidian</div><div class="titlebar-button-container mod-left" style="left: 0px;"></div><div class="titlebar-button-container mod-right"><div class="titlebar-button mod-minimize" aria-label="Minimize"><svg aria-hidden="false" width="10" height="10" viewBox="0 0 12 12"><rect fill="currentColor" width="10" height="1" x="1" y="6"></rect></svg></div><div class="titlebar-button mod-close" aria-label="Close window"><svg aria-hidden="false" width="10" height="10" viewBox="0 0 12 12"><polygon fill="currentColor" fill-rule="evenodd" points="11 1.576 6.583 6 11 10.424 10.424 11 6 6.583 1.576 11 1 10.424 5.417 6 1 1.576 1.576 1 6 5.417 10.424 1"></polygon></svg></div></div></div></div>
<div class="starter-screen"><div class="starter-screen-inner"><div class="recent-vaults"><div class="recent-vaults-list"><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Vault for MBA</div><div class="recent-vaults-list-item-path">E:\Arasan\21.4\Vault for MBA</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Vault La MBA</div><div class="recent-vaults-list-item-path">E:\Vault La MBA</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Obsidian Help</div><div class="recent-vaults-list-item-path">C:\Users\Ahmed\AppData\Roaming\obsidian\Obsidian Help</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">q</div><div class="recent-vaults-list-item-path">C:\Users\Ahmed\Documents\Adobe\q</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Test Vault</div><div class="recent-vaults-list-item-path">C:\Users\Ahmed\Documents\Waste for now\Test Vault</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Vault de MBA</div><div class="recent-vaults-list-item-path">E:\Vault de MBA</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div></div></div><div class="splash"><div class="splash-brand"><svg viewBox="0 0 100 100" class="logo-crystal" width="60" height="60"><defs><linearGradient id="a" x1="82.85" y1="30.41" x2="51.26" y2="105.9" gradientTransform="matrix(1, 0, 0, -1, -22.41, 110.97)" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#6c56cc"></stop><stop offset="1" stop-color="#9785e5"></stop></linearGradient></defs><polygon points="62.61,0 30.91,17.52 18,45.45 37.57,90.47 65.35,100 70.44,89.8 81,26.39 62.61,0" fill="#34208c"></polygon><polygon points="81,26.39 61.44,14.41 34.43,35.7 65.35,100 70.44,89.8 81,26.39" fill="url(#a)"></polygon><polygon points="81,26.39 81,26.39 62.61,0 61.44,14.41 81,26.39" fill="#af9ff4"></polygon><polygon points="61.44,14.41 62.61,0 30.91,17.52 34.43,35.7 61.44,14.41" fill="#4a37a0"></polygon><polygon points="34.43,35.7 37.57,90.47 65.35,100 34.43,35.7" fill="#4a37a0"></polygon></svg><div class="splash-brand-name">Obsidian</div><div class="splash-brand-version">Beta version 0.12.3</div></div><div class="open-vault-options-container"><div class="open-vault-options mod-open-vault"><div class="setting-item"><div class="setting-item-info"><div class="setting-item-name">Open folder as vault</div><div class="setting-item-description">Choose an existing folder of Markdown files.</div></div><div class="setting-item-control"><button>Open</button></div></div><div class="setting-item"><div class="setting-item-info"><div class="setting-item-name">Create new vault</div><div class="setting-item-description">Create a new Obsidian vault under a folder.</div></div><div class="setting-item-control"><button>Create</button></div></div><div class="setting-item"><div class="setting-item-info"><div class="setting-item-name">Open help vault</div><div class="setting-item-description">Open a "Demo &amp; Help" vault.</div></div><div class="setting-item-control"><button>Help</button></div></div><div class="setting-item mod-change-language"><div class="setting-item-info"><div class="setting-item-name"><svg viewBox="0 0 100 100" class="languages" width="30" height="30"><path fill="currentColor" stroke="currentColor" d="M50,4C24.7,4,4,22.7,4,46c0,9.9,3.8,19,10.1,26.1H14c0.8,1.3,0.9,2.9,0.4,4.8c-0.4,1.9-1.4,4.1-2.6,6.1 c-1.2,2-2.5,3.8-3.6,5.3c-0.5,0.7-1,1.3-1.4,1.8c-0.2,0.2-0.3,0.5-0.4,0.7C6.3,91.1,6,91.1,6,92.2C6,93,6.3,94,7.1,94.8 c0.8,0.8,1.9,1.2,3.3,1.2c9.2,0,17.6-6.9,24-10.6C39.3,87,44.5,88,50,88c25.3,0,46-18.7,46-42S75.3,4,50,4L50,4z M50,8 c23.3,0,42,17.1,42,38S73.3,84,50,84c-5.4,0-10.6-0.9-15.3-2.6l-0.9-0.3l-0.8,0.5c-6.9,4-15.3,10.4-22.6,10.4 c0.3-0.4,0.5-0.7,0.9-1.2c1.1-1.5,2.5-3.5,3.8-5.7s2.5-4.7,3.1-7.3c0.6-2.6,0.5-5.3-0.9-7.8l-0.1-0.2l-0.1-0.1 C11.5,63.2,8,55,8,46C8,25.1,26.7,8,50,8L50,8z M32.7,24c-0.7,0.1-1.3,0.7-1.6,1.4l-6.1,17.5c-0.2,0.3-0.4,0.7-0.4,1.1l-2.6,7.4 c-0.4,0.7-0.3,1.5,0.2,2.2c0.5,0.6,1.3,0.9,2.1,0.7c0.8-0.2,1.3-0.8,1.5-1.6l2.3-6.6h9.6l2.3,6.6c0.1,0.8,0.7,1.4,1.5,1.6 c0.8,0.2,1.6-0.1,2.1-0.7c0.5-0.6,0.6-1.5,0.2-2.2l-9-26C34.6,24.4,33.7,23.9,32.7,24z M33,32.1l3.4,9.9h-6.9L33,32.1z M65.8,37.9 c-0.1,0-0.2,0-0.3,0.1c-0.9,0.2-1.6,1-1.6,2v4H54c-0.1,0-0.1,0-0.2,0c-0.1,0-0.1,0-0.2,0c-1.1,0.1-1.9,1.1-1.8,2.2 s1.1,1.9,2.2,1.8h17.4c-0.8,2.6-2.6,7.1-6.6,11.1c-3.4-3.4-4.9-6.2-4.9-6.2c-0.4-0.7-1.2-1.2-2-1.1c-0.7,0.1-1.3,0.5-1.6,1.1 c-0.3,0.6-0.3,1.3,0.1,1.9c0,0,1.7,3.1,5.4,6.8c-2.3,1.7-5,3.3-8.4,4.4c-0.8,0.1-1.4,0.7-1.6,1.5c-0.2,0.8,0.1,1.6,0.7,2.1 c0.6,0.5,1.5,0.6,2.2,0.2c4.1-1.4,7.4-3.4,10.1-5.5c2.3,1.9,5.1,3.8,8.4,5.4c1,0.5,2.2,0.1,2.7-0.9c0.5-1,0.1-2.2-0.9-2.7 c-2.8-1.4-5.2-2.9-7.2-4.5c5.1-5.3,7.1-11,7.9-13.7H78c0.7,0,1.4-0.4,1.8-1c0.4-0.6,0.4-1.4,0-2c-0.4-0.6-1-1-1.8-1H68v-4 c0-0.6-0.2-1.1-0.6-1.5C67,38.1,66.4,37.9,65.8,37.9z"></path></svg></div><div class="setting-item-description"></div></div><div class="setting-item-control"><select class="dropdown"><option value="en">English</option><option value="zh">简体中文</option><option value="zh-TW">繁體中文</option><option value="ru">Pусский</option><option value="ko">한국어</option><option value="it">Italiano</option><option value="id">Bahasa Indonesia</option><option value="ro">Română</option><option value="pt-BR">Portugues do Brasil</option><option value="cz">čeština</option><option value="de">Deutsch</option><option value="es">Español</option><option value="fr">Français</option><option value="no">Norsk</option><option value="pl">język polski</option><option value="pt">Português</option><option value="ja">日本語</option><option value="da">Dansk</option><option value="tr">Türkçe (kısmi)</option><option value="hi">हिन्दी (आंशिक)</option><option value="nl">Nederlands (gedeeltelijk)</option><option value="ar">العربية (جزئي)</option></select></div></div></div></div></div></div></div>
<script type="text/javascript" src="lib/i18next.min.js"></script>
<script type="text/javascript" src="starter.js"></script>


</body></html>

---

<html><head>
    <meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
    <title>Obsidian</title>
	<link href="app.css" type="text/css" rel="stylesheet">
</head>
<body class="theme-dark starter is-frameless" style="padding-top: 24px;"><div class="titlebar" style="height: 24px; padding-top: 2px;"><div class="titlebar-inner"><div class="titlebar-left"></div><div class="titlebar-text">Obsidian</div><div class="titlebar-button-container mod-left" style="left: 0px;"></div><div class="titlebar-button-container mod-right"><div class="titlebar-button mod-minimize" aria-label="Minimize"><svg aria-hidden="false" width="10" height="10" viewBox="0 0 12 12"><rect fill="currentColor" width="10" height="1" x="1" y="6"></rect></svg></div><div class="titlebar-button mod-close" aria-label="Close window"><svg aria-hidden="false" width="10" height="10" viewBox="0 0 12 12"><polygon fill="currentColor" fill-rule="evenodd" points="11 1.576 6.583 6 11 10.424 10.424 11 6 6.583 1.576 11 1 10.424 5.417 6 1 1.576 1.576 1 6 5.417 10.424 1"></polygon></svg></div></div></div></div>
<div class="starter-screen"><div class="starter-screen-inner"><div class="recent-vaults"><div class="recent-vaults-list"><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Vault for MBA</div><div class="recent-vaults-list-item-path">E:\Arasan\21.4\Vault for MBA</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Vault La MBA</div><div class="recent-vaults-list-item-path">E:\Vault La MBA</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Obsidian Help</div><div class="recent-vaults-list-item-path">C:\Users\Ahmed\AppData\Roaming\obsidian\Obsidian Help</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">q</div><div class="recent-vaults-list-item-path">C:\Users\Ahmed\Documents\Adobe\q</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Test Vault</div><div class="recent-vaults-list-item-path">C:\Users\Ahmed\Documents\Waste for now\Test Vault</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div><div class="recent-vaults-list-item"><div class="recent-vaults-list-item-name">Vault de MBA</div><div class="recent-vaults-list-item-path">E:\Vault de MBA</div><div class="recent-vaults-list-item-delete-button"><svg viewBox="0 0 100 100" class="cross" width="12" height="12"><path fill="currentColor" stroke="currentColor" d="M15.4,12.6l-2.9,2.9L47.1,50L12.6,84.6l2.9,2.9L50,52.9l34.6,34.6l2.9-2.9L52.9,50l34.6-34.6l-2.9-2.9L50,47.1L15.4,12.6z "></path></svg></div></div></div></div><div class="splash"><div class="splash-brand"><svg viewBox="0 0 100 100" class="logo-crystal" width="60" height="60"><defs><linearGradient id="a" x1="82.85" y1="30.41" x2="51.26" y2="105.9" gradientTransform="matrix(1, 0, 0, -1, -22.41, 110.97)" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#6c56cc"></stop><stop offset="1" stop-color="#9785e5"></stop></linearGradient></defs><polygon points="62.61,0 30.91,17.52 18,45.45 37.57,90.47 65.35,100 70.44,89.8 81,26.39 62.61,0" fill="#34208c"></polygon><polygon points="81,26.39 61.44,14.41 34.43,35.7 65.35,100 70.44,89.8 81,26.39" fill="url(#a)"></polygon><polygon points="81,26.39 81,26.39 62.61,0 61.44,14.41 81,26.39" fill="#af9ff4"></polygon><polygon points="61.44,14.41 62.61,0 30.91,17.52 34.43,35.7 61.44,14.41" fill="#4a37a0"></polygon><polygon points="34.43,35.7 37.57,90.47 65.35,100 34.43,35.7" fill="#4a37a0"></polygon></svg><div class="splash-brand-name">Obsidian</div><div class="splash-brand-version">Beta version 0.12.3</div></div><div class="open-vault-options-container"><div class="open-vault-options mod-create-vault" style=""><div class="back-button">&lt;- Back</div><div class="setting-item"><div class="setting-item-info"><div class="setting-item-name">Vault name</div><div class="setting-item-description">Pick a name for your awesome vault.</div></div><div class="setting-item-control"><input type="text" spellcheck="false" placeholder="Vault name"></div></div><div class="setting-item"><div class="setting-item-info"><div class="setting-item-name">Location</div><div class="setting-item-description">Pick a place to put your new vault.</div></div><div class="setting-item-control"><button>Browse</button></div></div><div class="u-center-text"><button class="mod-cta">Create</button></div></div></div></div></div></div>
<script type="text/javascript" src="lib/i18next.min.js"></script>
<script type="text/javascript" src="starter.js"></script>


</body></html>
  
