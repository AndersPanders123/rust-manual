1. 

Får å starte ett Rust prosjekt må du først laste det ned fra rust sin nettside: https://www.rust-lang.org/tools/install 
Da velger du 32 bit eller 64 bit. 

2. 

Etter du har lastet den ned og åpnet filen som heter: rustup-init.exe  
Du vil få opp en vindu i cmd , skriv in 1 så Enter i terminalen. 

3. 

Når den er ferdig med å laste ned vil terminalen lukke seg. Da har du rust lastet ned. Får å faktisk starte ett prosjekt må du åpne terminalen. 

4. 

Nå må du finne pathen til mappen du vil ha prosjektet ditt.  
Her er min path: C:\Users\Ander\OneDrive\Documents\GitHub\rust-manual
Du kan finne pathen med å finne mappen i file exporer, når du har mappen kan du bare kopiere pathen med ctrl c, ctrl v.

5. 

Gå tilbake til terminalen og skriv: cd C:\Users\Ander\OneDrive\Documents\GitHub\rust-manual (ikke skriv min path med din egen)  
cd står for change directory og betyr at du bytter mappe i terminalen.

6. 

Rust bruker noe som heter cargo, det skal du skrive foran kommandoer som for eksempel: cargo run, som runner koden. 
Får å lage prosjektet skriver du: cargo new navnPåProsjekt. Så trykker du på enter 
Da lager du en mappe med rust prosjektet ditt.
Nå som du har en mappe med rust prosjektet ditt på kan du bare lukke terminalen. 

7. 

Da ligger rust dokumentet i mappen du lagde i terminalen. Nå kan du åpne vscode og åpne mappen der, da ser du at det er flere filer, 
src
  main.rs
target
Cargo.lock
Cargo.toml

Du skal srive i main.rs eller bare lage en til rs fil i mappen.
Mappen target trenger du ikke å tenke så mye på så bare la den være.

8. 

Nå er det bare å lage det du ønsker. 
Det vill allerede være et script der dit kommer til å være:
fn main() {
  println!("Hello, world!");
}
 Du kan bare fjerne det så gjøre hva du vil. Jeg ambefaler og laste ned en vscode extension som heter rust_analyser
