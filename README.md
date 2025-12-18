# CLIP_product_search
1. Preparing for dataset (images, text description)
    Dataset: https://www.kaggle.com/datasets/nirmalsankalana/fashion-product-text-images-dataset
2. Fine-tune CLIP model
    Model: openai/clip-vit-base-patch32
    Best result on CPU:
        Train Loss: 0.3536
        Train CLIP Score: 0.8407
        Val CLIP Score: 0.8267
3. Search for relevant products
    High precision and efficiency! Example:

    ============================================================
    Результаты поиска по запросу: 'red skirt'
    ============================================================

    ![alt text](image.png)

    Score: 0.9362
1.  Описание: composition red skirt made of 100% cotton, has an elasticated waistband, two patch pockets on the back, a zipper fly, and brand name      embroidered above the left hem in silver fitting regular wash care machine wash separately in cold water using a mild detergent do not bleach or soak line dry inside out in shade warm iron only do not iron directly on printembroidery the cute statement simply zooms high when you dress your little girl in this skort from gini and jony. the shorts and box pleats offer her absolute comfort to move around in ease, while the fabric keeps her fresh and comfortable all day. team this with a t-shirt or girly tops, and sandals, and let your little one play in much comfort.
   Путь: 13305.jpg

2. Score: 0.9362
   Описание: composition red skort made of 100% cotton, has an elasticated waistband, two patch pockets on the back, a zipper fly, and brand name embroidered above the left hem in silver fitting regular wash care machine wash separately in cold water using a mild detergent do not bleach or soak line dry inside out in shade warm iron only do not iron directly on printembroidery the cute statement simply zooms high when you dress your little girl in this skort from gini and jony. the shorts and box pleats offer her absolute comfort to move around in ease, while the fabric keeps her fresh and comfortable all day. team this with a t-shirt or girly tops, and sandals, and let your little one play in much comfort.
   Путь: 13304.jpg

3. Score: 0.9113
   Описание: skirts fabindia women red skirts
   Путь: 32252.jpg

4. Score: 0.9109
   Описание: composition coral shorts made of 100% cotton, with elasticated waist, two patch pockets on the back with buttoned flaps, pleated foldover flap on the front and embroidered brand name on the left side of flap fitting regular waist - 22-24 inches wash care machine wash cold water wash with like colours washdry inside out use mild detergents do not tumble dry use warm iron do not iron on decor remove all detachable get ready to indulge your little girl in the spirit of summer with these coral skorts from gini and jony. team this with white tees and comfy crocs footwear for a happy, casual outing with her small buddies, while the soft fabric stays soft on her skin and keeps her fresh and comfortable all day.
   Путь: 5005.jpg

5. Score: 0.8920
   Описание: style note femella caters to every fashionista. this skirt from femella is perfect for those who love the exotic. pair it with a solid coloured top, a vibrant scarf and knee high boots. product details black red skirt, has a comfortable fabric waist, and has a zippered closure at the back material and care blended fabric machine wash with similar colours do not bleach or dry in direct sunlight use warm iron if needed size and fit regular fit the model height 58 and waist 26 is wearing a size m
   Путь: 25931.jpg
