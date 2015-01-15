### Asennus

TMC-netbeansin asennus menee [Developer setup](https://github.com/tmc-langs/tmc-netbeans) ohjeiden mukaan. Jos `Tools -> NetBeans Platforms` kohtaa ei löydy, voi **tmc-netbeans** projektin avata NetBeansiin jolloin `Tools -> NetBeans Platforms` ilmestyy josta voi ladatun NetBeansin lisätä NetBeans Platformeihin. NetBeansin pitäisi tunnistaa uusi ympäristö automaattiseti jos näin ei ole voi projektin asetusten `Libraries` kohdasta vaihtaa käytettävä NetBeans Platform. 

### SelectedTailoring

Ohjeissa mainittu SelectedTailoring onnistuu tekemällä vain uusi tiedosto **SelectedTailoring.properties** ja lisäämällä sinne `defaultTailoring=fi.helsinki.cs.tmc.tailoring.DeveloperTailoring`
