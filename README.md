Lien vers le tutorial Angular2 "tour of heroes" : https://angular.io/docs/ts/latest/tutorial/

#### Observations

```
<li *ngFor="let hero of heroes"
  [class.selected]="hero === selectedHero"
  (click)="onSelect(hero)">
```

- `*` devant `ngFor`
- `class.selected` est entre crochets `[` et `]`
- `click` est entouré de parenthèses `(` et `)`

#### Démarrage

```
npm install
npm start
```
