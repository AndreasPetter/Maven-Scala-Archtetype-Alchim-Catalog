# Maven-Scala-Archtetype-Alchim-Catalog

For Eclipse or Scala-IDE, to get maven archetypes listed in the list of possible archetypes one needs to have an archetype catalog.

The file https://github.com/AndreasPetter/Maven-Scala-Archtetype-Alchim-Catalog/blob/master/catalog-maven-archetype-alchim31.xml adds the maven archetype ```net.alchim31.maven:scala-archetype-simple:1.6```.

To achieve that first check out the file, e.g. by doing ```git clone https://github.com/AndreasPetter/Maven-Scala-Archtetype-Alchim-Catalog.git```. Remember the path.

Then, in Eclipse/Scala-IDE click on ```Window->Preferences->Maven->Maven Archetypes->Add Local Catalog``` browse for the catalog file and give a name, e.g. "Simple Maven Archetype for Scala by Alchim31".

Afterwards the archetype should appear in the list of archetypes when doing the ```New->Maven->Maven Project->Next``` process and by optionally providing the filter critria "scala".

This is provided as is wihout any warranty whatsoever.