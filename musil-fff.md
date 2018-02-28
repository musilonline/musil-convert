Musil in folio flat file format 
======

For fff in general, see [musil-convert.md#folio-flat-file-format-fff](https://github.com/musilonline/musil-convert/blob/master/musil-convert.md#folio-flat-file-format-fff).

## examples

### alternative variants
![grafik](https://user-images.githubusercontent.com/10358005/36734728-ab289ec2-1bd4-11e8-8b50-71721a3caed6.png)
(Mappe Druckfahnen, p.&nbsp;5, Ausschnitt; cf. corresponding [TEI encoding](https://github.com/musilonline/musil-xml/blob/66e272cba88c0e0f7f234f81dcb4ec24520c5137/druckfahnen_kap39-41_version2018-02-21kg.xml#L638))

Rendering of this passage in Folio Views (2009 update):
![grafik](https://user-images.githubusercontent.com/10358005/36738585-2c048548-1bde-11e8-8f8f-766cc05ebbf7.png)

Corresponding fff code (lineation original):
```
<RD><GR:"Band 3"><CS:ZEILENZAHL>3</CS> die Gesundheit auf den tierischen Teil des Menschen zu gründen,
<RD><GR:"Band 3"><CS:ZEILENZAHL>4</CS> geistiger und sittlicher Adel sind es vielmehr, woraus die körperliche
<RD><GR:"Band 3"><CS:ZEILENZAHL>5</CS> Widerstandsfähigkeit hervorgeht; und wenn °das auch nicht immer
<RD><GR:"Band 3"><CS:ZEILENZAHL>6</CS> auf den #E#<FT:Wingdings,FX,SY>n<FT>\e<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein rechts.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>inzelnen zutrifft, *so #d# <FT:Wingdings,FX,SY>n<FT>\°°trifft es
<RD><GR:"Band 3"><CS:ZEILENZAHL>7</CS>  d°°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein links.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>afür* <FT:Wingdings,FX,SY>n<FT>\°°*so wirkt es doch* *tut es das*°°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein links.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT> umso 
<RD><GR:"Band 3"><CS:ZEILENZAHL>8</CS> sicherer im #G#<FT:Wingdings,FX,SY>n<FT>\g<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein rechts.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>roßen<FT:Wingdings,FX,SY>n<FT>\°°zu°°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein rechts.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>,
<RD><GR:"Band 3"><CS:ZEILENZAHL>9</CS> denn die Kraft eines Volkes ist die Folge des rechten Geistes, und
<RD><GR:"Band 3"><CS:ZEILENZAHL>10</CS> nicht gilt es umgekehrt. Lindner hatte darum seinen Abreibungen auch
<RD><GR:"Band 3"><CS:ZEILENZAHL>11</CS> eine besondere und sorgfältige Ausbildung°<PX:"NUMMERN-POPUP","50_1">«50_1»<EL> angedeihen lassen, die
<RD><GR:"Band 3"><CS:ZEILENZAHL>12</CS> es vermied, mit rücksichtslosem Zugreifen den üblichen männlichen
```

Corresponding fff code with flexible line breaks:

`<RD><GR:"Band 3"><CS:ZEILENZAHL>3</CS> die Gesundheit auf den tierischen Teil des Menschen zu gründen,`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>4</CS> geistiger und sittlicher Adel sind es vielmehr, woraus die körperliche`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>5</CS> Widerstandsfähigkeit hervorgeht; und wenn °das auch nicht immer`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>6</CS> auf den #E#<FT:Wingdings,FX,SY>n<FT>\e<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein rechts.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>inzelnen zutrifft, *so #d# <FT:Wingdings,FX,SY>n<FT>\°°trifft es`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>7</CS>  d°°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein links.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>afür* <FT:Wingdings,FX,SY>n<FT>\°°*so wirkt es doch* *tut es das*°°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein links.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT> umso` 

`<RD><GR:"Band 3"><CS:ZEILENZAHL>8</CS> sicherer im #G#<FT:Wingdings,FX,SY>n<FT>\g<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein rechts.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>roßen<FT:Wingdings,FX,SY>n<FT>\°°zu°°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein rechts.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>,`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>9</CS> denn die Kraft eines Volkes ist die Folge des rechten Geistes, und`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>10</CS> nicht gilt es umgekehrt. Lindner hatte darum seinen Abreibungen auch`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>11</CS> eine besondere und sorgfältige Ausbildung°<PX:"NUMMERN-POPUP","50_1">«50_1»<EL> angedeihen lassen, die`

`<RD><GR:"Band 3"><CS:ZEILENZAHL>12</CS> es vermied, mit rücksichtslosem Zugreifen den üblichen männlichen`

### deleted and restored
![grafik](https://user-images.githubusercontent.com/10358005/36736595-534e5458-1bd9-11e8-9895-0ae2909f2a48.png)
(Mappe Druckfahnen, p.&nbsp;7, Ausschnitt; cf. corresponding [TEI encoding](https://github.com/musilonline/musil-xml/blob/66e272cba88c0e0f7f234f81dcb4ec24520c5137/druckfahnen_kap39-41_version2018-02-21kg.xml#L792))

Rendering of this passage in Folio Views (2009 update):
![grafik](https://user-images.githubusercontent.com/10358005/36738879-e4378958-1bde-11e8-8c57-8fa606a8c34e.png)

Corresponding fff code (lineation original):
```
<RD><GR:"Band 3"><CS:ZEILENZAHL>22</CS> Sekunden, von der Freude am industriösen Geist der Menschheit
<RD><GR:"Band 3"><CS:ZEILENZAHL>23</CS> überwunden, der sogar in solchen geringfügigen Fertigkeiten und ihrem
<RD><GR:"Band 3"><CS:ZEILENZAHL>24</CS> Erwerbe steckt, °w°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Durch Unterpunktung Rotstift aufgehobene Streichung.<LT>°<FT:Wingdings,FX,SY><EL>n<FT>\°#d#°<PW:"POPUP Erläuterung ",2.27083,1.54167,"Popup-Verknüpfung">Bleistift Latein rechts; Streichung Rotstift.<LT>°<EL>|<FT:Wingdings,FX,SY>n<FT>essen sich der Gebildete heute zu
<RD><GR:"Band 3"><CS:ZEILENZAHL>25</CS> seinem allgemeinen Nachteil hochmütig überhoben dünkt! Mit Behagen hatte
```
