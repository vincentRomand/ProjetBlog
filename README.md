const data1 = {
  author: "Christian Peters",
  title: "Calculateur quantique",
  category: "Technologie",
  img: "https://randomuser.me/api/portraits/men/37.jpg",
  content: `
  Un calculateur quantique (anglais quantum computer, parfois traduit par ordinateur quantiquea, ou système informatique quantique2), utilise les propriétés quantiques de la matière, telle que la superposition et l'intrication afin d'effectuer des opérations sur des données. À la différence d'un ordinateur classique basé sur des transistors travaillant sur des données binaires (codées sur des bits, valant 0 ou 1), le calculateur quantique travaille sur des qubits dont l'état quantique peut posséder une infinité de valeurs.

De petits calculateurs quantiques ont été construits à partir des années 1990. Jusqu'en 2008, la difficulté majeure concerne la réalisation physique de l'élément de base : le qubit. Le phénomène de décohérence (perte des effets quantiques en passant à l'échelle macroscopique) freine le développement des calculateurs quantiques. Le premier processeur quantique est créé en 2009 à l'université Yale : il comporte deux qubits composés chacun d'un milliard d'atomes d'aluminium posés sur un support supraconducteur.

Ce domaine est soutenu financièrement par plusieurs organisations, entreprises ou gouvernements en raison de l'importance de l'enjeu : au moins un algorithme conçu pour utiliser un circuit quantique, l'algorithme de Shor, rendrait possible de nombreux calculs combinatoiresb hors de portée d'un ordinateur classique en l'état actuel des connaissances. La possibilité de casser les méthodes cryptographiques classiques est souvent mise en avant.
  `
};

const data2 = {
  author: "Mattie Murphy",
  title: "The Witcher",
  category: "Cinema",
  img: "https://randomuser.me/api/portraits/women/18.jpg",
  content: `
  The Witcher is an American fantasy drama series produced by Lauren Schmidt Hissrich. It is based on the book series of the same name by Polish writer Andrzej Sapkowski. The first season, consisting of eight episodes, was released on Netflix in its entirety on December 20, 2019. A second season was announced for release in 2021.

Set in a medieval fictional world on a landmass known as "the Continent", The Witcher follows the story of solitary monster hunter Geralt of Rivia (Henry Cavill), sorceress Yennefer of Vengerberg (Anya Chalotra) and Cintran princess Ciri (Freya Allan), who find their destinies tied together. The first season is based on The Last Wish and Sword of Destiny, a collection of short stories which precede the main Witcher saga. The first season explores formative events that shaped the three lead characters, prior to their first encounters with each other.
  `
};

const data3 = {
  author: "Eli Perry",
  title: "Marc Aurèle",
  category: "Histoire",
  img: "https://randomuser.me/api/portraits/men/12.jpg",
  content: `
  Son grand-père Marcus Annius Verus, consul et préfet de Rome, fut agrégé aux patriciens par les empereurs Vespasien et Titus pendant leur censure. Son oncle paternel Marcus Annius Libo fut consul ; sa tante Faustine l'Ancienne porta le titre d'Augusta. Son père Marcus Annius Verus fut préteur à Rome. Sa mère Domitia Lucilla était fille de Publius Calvisius Tullus Ruso, qui avait obtenu le consulat éponyme en 109. Son bisaïeul paternel, Marcus Annius Verus était originaire de la colonie césarienne d'Ucubi (actuelle Espejo en Espagne), il devint sénateur et exerça la préture3,4. Son bisaïeul maternel, Lucius Catilius Severus, fut deux fois consul et préfet de Rome. Son aïeule paternelle était Rupilia Faustina, fille du consulaire Rupilius Bonus5.

Marc Aurèle naquit à Rome le six des calendes de mai (26 avril 121), dans les jardins du Cælius, sous le second consulat de son aïeul et sous celui d'Augur, au sein d'une famille italienne qui vécut longtemps en Espagne. Il fut élevé à l'endroit même où il naquit, et dans la maison de son aïeul Verus près du palais de Latran. Il eut une sœur plus jeune que lui, nommée Annia Cornificia.

À sa naissance, il porta d'abord une partie du nom de son aïeul Marcus Annius Verus et de son bisaïeul maternel Lucius Catilius Severus. Après la mort de son père en 124, il fut élevé et adopté par son aïeul paternel. Sous le nom de Marcus Annius Verus, il fut gouverneur de Rome après avoir pris la toge virile dans sa quinzième année. L'empereur Hadrien le prit sous sa protection, le nomma Annius Verissimus (Annius « le plus sincère ») et demanda en 138 à son fils adoptif, Antonin, de l'adopter à son tour (procédure d'adrogation) ainsi que Lucius Aurelius Verus, le fils de celui qu'Hadrien avait d'abord choisi comme héritier et qui venait de mourir. Après son adoption il devint Marcus Ælius Aurelius Verus6.
  `
};

console.log(JSON.stringify(data1));
console.log(JSON.stringify(data2));
console.log(JSON.stringify(data3));
