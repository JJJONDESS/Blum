# Blum AR Menu - v1 (based on Melt9 Promotion Food final v23)

Same AR menu as the Melt9 v23 final, rebranded for Blum.
Blum colours: red #E00102, light grey #E3E6EE, black #000000.
Glass box, red edges, red base, black BLUM logo plate,
fixed AR label, Add to cart + Photo in AR, self-hosted
libs/ engine. Works on iOS (Quick Look) and Android
(MindAR camera scan).

## IMPORTANT - dishes are placeholders for now
The 3 dishes in dishes.js are still the Melt9 pizzas
(McArt, MR-Pizza-Mayu, MR-VegPizza) with their 3D models
and photos, because Blum's menu was not given yet.
To make this a real Blum menu, send BOSS:
  1. Blum dish names + prices (3 dishes to start)
  2. A photo of each dish (for the menu + camera target)
  3. A 3D model of each dish (RealityScan, like Melt9)
Then dishes.js + the dishes/ folder get swapped to Blum's
dishes, and the Melt9 pizza files are removed.

## To change something
- Restaurant name / phone / WhatsApp: dishes.js, RESTAURANT
  (phone and WhatsApp are blank for now - the WhatsApp
  button hides until a number is added).
- Brand colours: index.html, search "BRAND COLOURS".
- Pizza size: dishes.js, scale: - change all 3 numbers.
- Box size: index.html, search "GLASS BOX".
