# Gayeongdang Hanok Culture Stay

An immersive, responsive hotel landing page for **청주 가영당한옥문화스테이** in Cheongju, South Korea.

**[View the live demo](https://gayeongdang-hanok-demo.muzaffaransoriy.chatgpt.site)**

## Experience

- Scroll directed Three.js hanok scene with reduced motion and WebGL fallback
- Room catalog with three original 3D concept visuals
- Mobile friendly navigation and SMS availability inquiry
- Location section with Kakao Map and Naver Map links

This is a design concept and inquiry experience. The room visuals are illustrative concepts, not photographs of the hotel's actual rooms. The site does not process bookings or payments.

## Run locally

Serve this directory with a local static server, for example:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. The site uses a Three.js ES module from jsDelivr and Google Fonts, so those features need an internet connection.

## Credits

The hanok reference photographs shown on the site are by [Basile Morin](https://commons.wikimedia.org/wiki/User:Basile_Morin), licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/): [golden hour hanok](https://commons.wikimedia.org/wiki/File:Traditional_hanok_houses_at_golden_hour_in_Bukchon_Hanok_Village_in_Seoul.jpg) and [wooden doors](https://commons.wikimedia.org/wiki/File:Traditional_hanok_house_with_wooden_doors_along_a_steeply_sloping_street_in_Bukchon_Hanok_Village_Seoul.jpg). The room concept visuals in `assets/` were generated for this project. Three.js is loaded from [jsDelivr](https://www.jsdelivr.com/package/npm/three) and is licensed under MIT.

Built by [Muzaffar Normurodov](https://github.com/MuzaffarJr).
