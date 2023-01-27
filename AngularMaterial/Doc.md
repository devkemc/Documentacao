# Documentação para topicos especificos angular material

- ## Recuperando paleta de cores background do tema:

```scss
$bg-color: map.get(
  $theme-color,
  background
); //recupera paleta de cores de background do tema
$fg-color: map.get(
  $theme-color,
  foreground
); //recupera paleta de cores de foreground do tema
$is-dark-theme: map.get(
  $color-config,
  "is-dark"
); //recupera um booleano que armazena se o tema está dark ou não
```

- ## Cores padrão recuperadas do background:
| Propriedade  | Valor  |
|---|---|
| status-bar  | black  |
| app-bar  | #212121  |
| background  | #303030  |
| hover  | rgba(255, 255, 255, 0.04)  |
| card  | #424242  |
| dialog  | #424242  |
| disabled-button  | rgba(255, 255, 255, 0.12)  |
| raised-button  | #424242  |
| focused-button  | rgba(255, 255, 255, 0.12)  |
| selected-button  | #212121  |
| selected-disabled-button | #424242 |
| disabled-button-toggle | black |
| unselected-chip | #616161 |
| disabled-list-option | rgba(255, 255, 255, 0.12) |
| tooltip | #616161 |

- ## Cores padrão recuperadas do foreground:

| Propriedade  | Valor  |
|---|---|
| base | white |
| divider | rgba(255, 255, 255, 0.12) |
| dividers | rgba(255, 255, 255, 0.12) |
| disabled | rgba(255, 255, 255, 0.5) |
| disabled-button | rgba(255, 255, 255, 0.3) |
| disabled-text | rgba(255, 255, 255, 0.5) |
| elevation | black |
| hint-text | rgba(255, 255, 255, 0.5) |
| secondary-text | rgba(255, 255, 255, 0.7) |
| icon | white |
| icons |  white |
| text | white |
| slider-min | white |
| slider-off | rgba(255, 255, 255, 0.3) |
| slider-off-active | rgba(255, 255, 255, 0.3) |

- ## Recuperando cor disponivel "background" no background:

```scss
background-color: mat.get-color-from-palette($bg-color, background);
```

- ## Recuperando cor disponivel "text" no foreground :

```scss
color: mat.get-color-from-palette($fg-color, text);
```
