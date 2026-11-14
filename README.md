# Tarot · Tirada de cartas

Página para tirarse las cartas del tarot: mazo completo de 78 cartas con diseño propio, inspirado en el tarot clásico.

**Verla en línea:** https://matimurad.github.io/tarot/

## Qué hace

- Tiradas: Carta del día, Pasado/presente/futuro, Situación y consejo, Amor y vínculos, Sí o no y Cruz Celta.
- Barajás, cortás el mazo y elegís vos las cartas del abanico, boca abajo.
- Cada carta trae su significado al derecho o invertida, la interpretación según la posición, un consejo y una lectura general que conecta todas las cartas.
- Las tiradas se guardan en el navegador de cada persona ("Mis tiradas").

## Cómo se barajan las cartas

Cada vez que barajás, el mazo se mezcla por completo (algoritmo Fisher–Yates) con el generador aleatorio criptográfico del navegador: todas las cartas tienen la misma probabilidad de quedar en cualquier lugar y cada una tiene 50% de probabilidad de salir invertida.

Todo está en un solo archivo, `index.html`.
