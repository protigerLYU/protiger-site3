# VIZK website

Three service areas: logistics and roller systems, circuit board fabrication and repair, and chain/belt transmission.

Buildless static website using the layout of protiger.net. Retains the existing VIZK trademark and WeChat QR code.

Production: https://vizk.cn/ from the main branch of protigerLYU/protiger-site3.

The complete original website is archived in protigerLYU/protiger-site5 at commit c1d0aeeb9a954d959097e3f8c0ea89b76d2b02ea. Its file tree matches source snapshot e03fcc5f45c69b9e0980c7c5c55d7bd86f07586c exactly (tree 6612c804e7d741d5fd697fe1411a52dad5a153a4).

An additional restoration branch remains at backup/vizk-before-rebuild-20261019 in protiger-site3. Keep GitHub Pages for vizk.cn on protiger-site3 only; protiger-site5 is an archive.

## Timing pulley and belt illustration

Asset: `images/catalog/timing-pulleys-belts.webp` (880 x 660 WebP).

Created with the built-in image_gen tool as an illustrative catalogue image, not a photograph of a supplied product. The generated source was resized and encoded as WebP for the website.

Final prompt:

```text
Use case: product-mockup. Asset type: landscape 4:3 industrial spare-parts website catalogue image, one clean product photograph. Primary request: show synchronous timing pulleys together with a toothed timing belt, NOT rollers or flat belts. Subject: three silver machined aluminum synchronous timing pulleys of different diameters, each with physically plausible cylindrical axial tooth grooves, round flanges and a central shaft bore. Beside them, one black endless rubber synchronous timing belt, arranged in a relaxed oval loop in the foreground with the inner rows of evenly spaced rounded timing teeth clearly visible; its outer surface is smooth. All parts are separate, resting naturally on the surface. Backdrop: pure white seamless studio background, subtle soft contact shadows, ample white margin, no decorative elements. View: close three-quarter product view, crisp metal tooth edges and realistic black rubber teeth, balanced composition readable in a small sidebar image. Style: realistic professional industrial catalogue photography, neutral colors and soft diffuse light, no exaggerated reflections. No text, labels, model numbers, logos, watermark, chains, sprockets for chain drives, V-belts, multi-rib belts, conveyor rollers, electronics, people or tools. Exact engineering dimensions are not needed; focus on visually clear and mechanically plausible timing pulleys and toothed timing belt.
```

## Power Base and rack jack illustration

Asset: `images/catalog/power-base-rack-jack.webp` (880 x 660 WebP).

Created with the built-in image_gen tool as an unbranded category illustration of a four-point rack-jack synchronous lift. It is not a product photograph or an engineering drawing for a specific supplied model.

Structural reference: https://sunilpls.com/?page_id=2402 and https://sunilpls.com/wp-content/uploads/2022/04/RJ_600x400.jpg.

Final prompt:

```text
Use case: product-mockup. Asset type: industrial spare-parts website product image, landscape 4:3, white seamless studio background. Input image 1 is a STRUCTURAL REFERENCE ONLY for the form of a four-point rack-and-pinion synchronous lift similar to an RJ-4S arrangement; generate a new clean unbranded catalogue illustration. Subject: exactly four compact silver machined rack-jack gearboxes arranged at the four corners of a rectangle. Each corner gearbox has one straight vertical toothed RACK with a flat upper round mounting flange, not a threaded screw; the toothed racks are parallel and vertical. Slender horizontal transmission shafts and small right-angle gearboxes link the corner units to synchronize their motion, with one compact blue-grey gearmotor beside the near edge. Follow the reference for physically plausible connected shafts, four corner units and overall open rectangular structure. Show the whole assembly from a clear elevated three-quarter view, with generous white margin, visible gearboxes and racks, realistic metal finish and soft contact shadows. The subject must remain easy to recognize at sidebar thumbnail size. Photorealistic industrial catalogue product visualization; no dimensions or engineering callouts. No text, logos, labels, model numbers, watermark, added platform hiding the mechanism, conveyors, rollers, chains, scissor arms, threaded lead screws, people or tools. This is a category illustration, not a photograph of a specific supplied model.
```
