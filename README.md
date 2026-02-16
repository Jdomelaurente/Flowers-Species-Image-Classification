# Plant Species Image Classification

## A. Project Overview
This project is an image classification model designed to recognize 20 different species of flowers. Using a dataset of 5,000 images, the model was trained to distinguish between various floral structures, petal patterns, and colors. This tool can be used by gardeners or botany students to quickly identify common ornamental and wild flowers.

# Plant Species Gallery

## B. Plant Species Gallery

| Common Name | Scientific Name | Description | Image
| :--- | :--- | :--- | :--- |
| Anthurium | *Anthurium andraeanum* | Glossy, heart-shaped red bracts with a yellow spadix. |<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/82d4bc8e-2b37-4bba-9f77-a4f054fdbb03" />|
| Barbeton Daisy | *Gerbera jamesonii* | Large, brightly colored daisy-like flowers. |<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/45714aea-75d1-4f49-8780-48ab6eff57ff" />|
| Bougainvillea | *Bougainvillea glabra* | Woody vines with vibrant, paper-like colorful bracts. |<img width="225" height="224" alt="image" src="https://github.com/user-attachments/assets/527e1e7c-8de8-4788-b23d-c6c5e4a631c1" /> |
| Californian Poppy | *Eschscholzia californica* | Brilliant orange cup-shaped flowers. | <img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/ec3c73e1-56af-4b2b-9bc7-0a026447ac9a" />|
| Camellia | *Camellia japonica* | Symmetrical, rose-like flowers with glossy leaves. | <img width="227" height="222" alt="image" src="https://github.com/user-attachments/assets/cf1ccf12-8b05-4f4b-bbb9-92adcb20e963" />|
| Cape Flower | *Tecoma capensis* | Clusters of tubular, trumpet-like orange blooms. | <img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/5426e1b3-d791-4b4e-8017-423b449b25d7" />|
| Clematis | *Clematis viticella* | Large, star-shaped purple or pink climbing flowers. | <img width="171" height="295" alt="image" src="https://github.com/user-attachments/assets/1c932af0-a352-422d-85e0-be779860ce99" />|
| Cyclamen | *Cyclamen persicum* | Unique swept-back petals that point upwards. | <img width="222" height="227" alt="image" src="https://github.com/user-attachments/assets/69ae20a2-80dc-4b4c-a54d-eb8e72485c48" />|
| Geranium | *Pelargonium* | Clusters of small, five-petaled flowers on long stalks. | <img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/7841f281-1202-4b48-a96d-b625d3cac38f" />|
| Hibiscus | *Hibiscus rosa-sinensis* | Large trumpet-shaped blooms with a long stamen. | <img width="269" height="187" alt="image" src="https://github.com/user-attachments/assets/f7814da1-47a2-4983-bff1-e4590dd2b70c" />|
| Lotus | *Nelumbo nucifera* | Large, multi-petaled aquatic flowers. | <img width="235" height="215" alt="image" src="https://github.com/user-attachments/assets/988e164e-111e-422e-9570-67aa99c0d155" />|
| Morning Glory | *Ipomoea purpurea* | Funnel-shaped flowers that bloom in early morning. | <img width="273" height="185" alt="image" src="https://github.com/user-attachments/assets/f7b6407e-4aa2-495c-9495-aabe15f4dd9e" />|
| Passion Flower | *Passiflora edulis* | Complex flowers with a unique "fringe" of filaments. | <img width="224" height="224" alt="image" src="https://github.com/user-attachments/assets/76013d81-a637-497d-828b-4d909b5feeae" />|
| Petunia | *Petunia × atkinsiana* | Trumpet-shaped flowers in a wide variety of colors. | <img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/b1a723ff-038f-40f1-928d-727b9d19bdfe" />|
| Pink Yellow Dahlia | *Dahlia pinnata* | Multi-layered geometric petals in sunset gradients. | <img width="194" height="259" alt="image" src="https://github.com/user-attachments/assets/b1d233f2-e6e9-4fee-8dcf-478f079eee92" />|
| Sunflower | *Helianthus annuus* | Huge yellow ray flowers with a dark central disc. | <img width="213" height="236" alt="image" src="https://github.com/user-attachments/assets/a82a79cd-f34c-4f68-af83-a0927ef3d0d1" />|
| Sweet William | *Dianthus barbatus* | Small, fringed flowers in dense, flat-topped clusters. | <img width="271" height="186" alt="image" src="https://github.com/user-attachments/assets/cc85d114-fe74-4b23-aec0-e1262888e3c5" />|
| Sword Lily | *Gladiolus* | Tall spikes of ruffled, trumpet-shaped flowers. | <img width="194" height="259" alt="image" src="https://github.com/user-attachments/assets/9497208c-7ea2-4944-b4d1-f6f788f04dcc" />|
| Thorn Apple | *Datura stramonium* | Large, white upright trumpet flowers with spiky pods. |<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/91b144e2-2b5e-4cb9-9d63-a0dfffa47247" />|
| Wallflower | *Erysimum cheiri* | Fragrant, four-petaled flowers in warm earth tones. | <img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/19d81e56-9849-4734-bb6a-19100e937132" />|


## C. Model Training Details
- **Total Images:** 2,689 (Distributed across 20 classes)
- **Average Images per Class:** ~134 images (Note: some classes have more/less than others)
- **Epochs:** 100
- **Batch Size:** 64
- **Learning Rate:** 0.001

## D. Model Evaluation

![Confusion Matrix](loss.png)
![Accuracy Per Class](Accuracy.png)

## E. Model Testing

Below are 10 tests performed using images the model had not seen during training. These results demonstrate the model's ability to generalize and accurately identify plant species in various conditions.

---

### Test 1: Cyclamen
- **Result:** Correct
- **Confidence:** 96%
![Cyclamen Test](Cyclamen.png)

### Test 2: Geranium
- **Result:** Correct
- **Confidence:** 95%
![Geranium Test](Geranium.png)

### Test 3: Hibiscus
- **Result:** Correct
- **Confidence:** 99%
![Hibiscus Test](Hibiscus.png)

### Test 4: Anthurium
- **Result:** Correct
- **Confidence:** 96%
![Anthurium Test](Anthurium.png)

### Test 5: Barbeton Daisy
- **Result:** Correct
- **Confidence:** 97%
![Barbeton daisy Test](Barbeton_daisy.png)

### Test 6: Bougainvillea
- **Result:** Correct
- **Confidence:** 99%
![Bougainvillea Test](Bougainvillea.png)

### Test 7: Californian Poppy
- **Result:** Correct
- **Confidence:** 100%
![Californian_poppy Test](Californian_poppy.png)

### Test 8: Camellia
- **Result:** Correct
- **Confidence:** 100%
![Camellia Test](Camellia.png)

### Test 9: Cape Flower
- **Result:** Correct
- **Confidence:** 96%
![Cape_flower Test](Cape_flower.png)

### Test 10: Clematis
- **Result:** Correct
- **Confidence:** 98%
![Clematis Test](Clematis.png)

---
