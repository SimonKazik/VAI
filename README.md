Hello World App

Tento projekt je React Native aplikácia vytvorená pomocou príkazu:
  npx react-native@latest init FProject

Požiadavky
Pred spustením projektu sa uistite, že máte správne nastavené prostredie podľa oficiálneho návodu:
React Native Environment Setup

Krok 2: Spustenie Hello World Aplikácie
Tento projekt obsahuje niekoľko úprav (commits), ktoré slúžia na demonštráciu prvých cvičení.

Pre iOS
Naklonujte projekt a rozbaľte ho.

V koreňovom adresári projektu (napr. Documents/FProject) spustite:
  npm install
Tento príkaz nainštaluje všetky potrebné moduly (node_modules) používané v projekte.

Zmeňte adresár na ios a spustite:
  cd ios && pod install
Tento príkaz nainštaluje všetky potrebné pods pre iOS.

Vráťte sa do koreňového adresára a spustite aplikáciu:
  cd .. && npx react-native run-ios

Pre Android
Spustite aplikáciu príkazom:
  npx react-native run-android

Týmto by mala byť vaša aplikácia úspešne spustená na príslušnom zariadení. Ak narazíte na problémy, odporúčame preštudovať dokumentáciu React Native.
