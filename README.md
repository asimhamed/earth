# مجسم تضاريس الأرض

كرة أرضية ثلاثية الأبعاد تعرض تضاريس اليابسة وأعماق المحيطات الحقيقية، وتقرأ الارتفاع لأي نقطة.

- العرض: [MapLibre GL JS](https://maplibre.org) بإسقاط الكرة الأرضية.
- البيانات: [Terrain Tiles على AWS](https://registry.opendata.aws/terrain-tiles/) (Mapzen)، وتشمل ETOPO1 وGEBCO لقاع البحر وSRTM لليابسة. [مصادر البيانات وحقوقها](https://github.com/tilezen/joerd/blob/master/docs/attribution.md).

- الخرائط القديمة (109 خريطة تغطي 541 مليون سنة): [PALEOMAP PaleoDEMs](https://zenodo.org/records/5460860)، Scotese, C.R. & Wright, N. (2018)، برخصة CC BY 4.0. أُخذت النسخة المجمّعة بدقة درجة واحدة من مشروع [paleomap3D](https://github.com/afnleaf/paleomap3D) (CC BY 4.0)، وأُعيد ضغطها في `paleo.bin`.
- موقع الشمس يُحسب في المتصفح من الوقت الحالي.

الموقع ملف واحد (`index.html`) مع ملف البيانات `paleo.bin`، بدون أي خادم أو بناء، ويعمل مباشرة على GitHub Pages.
