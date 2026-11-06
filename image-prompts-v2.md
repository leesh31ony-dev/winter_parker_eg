# 이미지 교체 프롬프트 · 2026-11-06

내장 image_gen 도구를 사용했다. 로고 참조는 images/winter-parker-logo2.png이며, 메인 이미지 편집에는 기존 winter-collection.png도 함께 제공했다.

## 메인 이미지
Edit image 1 (three puffer jackets). Image 2 is the exact new Winter Parker brand logo reference. Preserve the three jackets, their cream/sand/taupe colors, all fabric texture, composition, lighting, seamless warm beige studio background and framing of image 1. Replace the old thin spider on center jacket with the solid white spider symbol from image 2 including its W-shaped negative space. Add that SAME new solid white spider symbol as small realistic embroidered chest branding on BOTH the left cream jacket AND right brown jacket. Each of all THREE jackets must have exactly one identical symbol on the wearer's LEFT chest (viewer RIGHT of zipper), at the same relative height and relative small size, scaled naturally to garment perspective. Use ONLY the white spider symbol, no rectangular brown background and no wordmark on the garments. The symbol must be clearly visible on all three. Do not alter garment shapes or add other objects. Wide landscape product photography.

결과: images/winter-collection-v2.png

## 단독 제품 이미지 공통 프롬프트
아래 SUBJECT를 각각의 제품 설명으로 바꿔 총 세 번 별도로 생성했다.

Use case product-mockup. Generate a NEW standalone luxury studio catalog photograph showing EXACTLY ONE SUBJECT. It must be a complete individual jacket photographed from the front, entire collar, both sleeves and hem fully in frame, floating ghost mannequin styling, no model, no hanger, NO other jackets. Reference image is the exact brand logo. Add a small crisp WHITE spider emblem matching the reference's solid silhouette, eight legs and W-shaped negative space to the wearer's LEFT chest (viewer RIGHT of zipper), at the standard chest-logo placement, realistic white embroidery. Emblem ONLY: no brown rectangle, no wordmark on garment. Refined lightweight quilted matte nylon, horizontal baffles, accurate zipper, soft fabric volume. Warm pale beige seamless studio background, subtle natural contact shadow, premium fashion product photography. Square composition, jacket centered with 12 percent clear margins on all sides. Consistent photographic lighting and palette with warm beige Winter Parker website. No text, no price, no watermark. This is a standalone individual product photograph, not a crop of a group photograph.

| 파일 | SUBJECT |
|---|---|
| images/men-jacket.png | adult MEN'S sand beige puffer jacket, broad slightly boxy shoulders, straight relaxed everyday silhouette |
| images/women-jacket.png | adult WOMEN'S ivory cream puffer jacket, softly shaped elegant short silhouette, slightly narrower shoulders |
| images/kids-jacket.png | CHILDREN'S dark taupe puffer jacket, clearly child-size proportions with a short compact torso and short small sleeves, rounded padded collar, safe simple design with NO drawcords |

## 적용 검증
- 1280px·375px 가로 넘침 없음.
- 새 로고 PNG와 단독 제품 이미지 3개 경로·로딩 확인.
- 단독 제품 이미지는 object-fit: contain, transform: none으로 온전히 표시.
- 키즈 필터 선택 시 kids-jacket.png만 표시됨을 확인.
- preview-products-v2.png에 실제 제품 영역 화면 저장.
