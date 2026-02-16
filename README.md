# Plant Species Image Classification

## A. Project Overview
This project is an image classification model designed to recognize 20 different species of flowers. Using a dataset of 5,000 images, the model was trained to distinguish between various floral structures, petal patterns, and colors. This tool can be used by gardeners or botany students to quickly identify common ornamental and wild flowers.

## B. Plant Species Gallery
| Common Name | Scientific Name | Description |
| :--- | :--- | :--- |
| Anthurium | *Anthurium andraeanum* | Glossy, heart-shaped red bracts with a yellow spadix. |
| Barbeton Daisy | *Gerbera jamesonii* | Large, brightly colored daisy-like flowers. |
| Bougainvillea | *Bougainvillea glabra* | Woody vines with vibrant, paper-like colorful bracts. |
| Californian Poppy | *Eschscholzia californica* | Brilliant orange cup-shaped flowers. |
| Camellia | *Camellia japonica* | Symmetrical, rose-like flowers with glossy leaves. |
| Cape Flower | *Tecoma capensis* | Clusters of tubular, trumpet-like orange blooms. |
| Clematis | *Clematis viticella* | Large, star-shaped purple or pink climbing flowers. |
| Cyclamen | *Cyclamen persicum* | Unique swept-back petals that point upwards. |
| Geranium | *Pelargonium* | Clusters of small, five-petaled flowers on long stalks. |
| Hibiscus | *Hibiscus rosa-sinensis* | Large trumpet-shaped blooms with a long stamen. |
| Lotus | *Nelumbo nucifera* | Large, multi-petaled aquatic flowers. |
| Morning Glory | *Ipomoea purpurea* | Funnel-shaped flowers that bloom in early morning. |
| Passion Flower | *Passiflora edulis* | Complex flowers with a unique "fringe" of filaments. |
| Petunia | *Petunia × atkinsiana* | Trumpet-shaped flowers in a wide variety of colors. |
| Pink Yellow Dahlia | *Dahlia pinnata* | Multi-layered geometric petals in sunset gradients. |
| Sunflower | *Helianthus annuus* | Huge yellow ray flowers with a dark central disc. |
| Sweet William | *Dianthus barbatus* | Small, fringed flowers in dense, flat-topped clusters. |
| Sword Lily | *Gladiolus* | Tall spikes of ruffled, trumpet-shaped flowers. |
| Thorn Apple | *Datura stramonium* | Large, white upright trumpet flowers with spiky pods. |
| Wallflower | *Erysimum cheiri* | Fragrant, four-petaled flowers in warm earth tones. |


https://readme.so/editor#:~:text=Plant%20Species%20Gallery%0A%0A%5BAdd%20image%20here%5D%0A%0A%23%23%20B.%20Plant%20Species%20Gallery%0A%0A%7C%20Common%20Name%20%7C%20Scientific%20Name%20%7C%20Description%20%7C%0A%7C%20%3A---%20%7C%20%3A---%20%7C%20%3A---%20%7C%0A%7C%20Anthurium%20%7C%20*Anthurium%20andraeanum*%20%7C%20Glossy%2C%20heart-shaped%20red%20bracts%20with%20a%20yellow%20spadix.%20%7C%0A%7C%20Barbeton%20Daisy%20%7C%20*Gerbera%20jamesonii*%20%7C%20Large%2C%20brightly%20colored%20daisy-like%20flowers.%20%7C%0A%7C%20Bougainvillea%20%7C%20*Bougainvillea%20glabra*%20%7C%20Woody%20vines%20with%20vibrant%2C%20paper-like%20colorful%20bracts.%20%7C%0A%7C%20Californian%20Poppy%20%7C%20*Eschscholzia%20californica*%20%7C%20Brilliant%20orange%20cup-shaped%20flowers.%20%7C%0A%7C%20Camellia%20%7C%20*Camellia%20japonica*%20%7C%20Symmetrical%2C%20rose-like%20flowers%20with%20glossy%20leaves.%20%7C%0A%7C%20Cape%20Flower%20%7C%20*Tecoma%20capensis*%20%7C%20Clusters%20of%20tubular%2C%20trumpet-like%20orange%20blooms.%20%7C%0A%7C%20Clematis%20%7C%20*Clematis%20viticella*%20%7C%20Large%2C%20star-shaped%20purple%20or%20pink%20climbing%20flowers.%20%7C%0A%7C%20Cyclamen%20%7C%20*Cyclamen%20persicum*%20%7C%20Unique%20swept-back%20petals%20that%20point%20upwards.%20%7C%0A%7C%20Geranium%20%7C%20*Pelargonium*%20%7C%20Clusters%20of%20small%2C%20five-petaled%20flowers%20on%20long%20stalks.%20%7C%0A%7C%20Hibiscus%20%7C%20*Hibiscus%20rosa-sinensis*%20%7C%20Large%20trumpet-shaped%20blooms%20with%20a%20long%20stamen.%20%7C%0A%7C%20Lotus%20%7C%20*Nelumbo%20nucifera*%20%7C%20Large%2C%20multi-petaled%20aquatic%20flowers.%20%7C%0A%7C%20Morning%20Glory%20%7C%20*Ipomoea%20purpurea*%20%7C%20Funnel-shaped%20flowers%20that%20bloom%20in%20early%20morning.%20%7C%0A%7C%20Passion%20Flower%20%7C%20*Passiflora%20edulis*%20%7C%20Complex%20flowers%20with%20a%20unique%20%22fringe%22%20of%20filaments.%20%7C%0A%7C%20Petunia%20%7C%20*Petunia%20%C3%97%20atkinsiana*%20%7C%20Trumpet-shaped%20flowers%20in%20a%20wide%20variety%20of%20colors.%20%7C%0A%7C%20Pink%20Yellow%20Dahlia%20%7C%20*Dahlia%20pinnata*%20%7C%20Multi-layered%20geometric%20petals%20in%20sunset%20gradients.%20%7C%0A%7C%20Sunflower%20%7C%20*Helianthus%20annuus*%20%7C%20Huge%20yellow%20ray%20flowers%20with%20a%20dark%20central%20disc.%20%7C%0A%7C%20Sweet%20William%20%7C%20*Dianthus%20barbatus*%20%7C%20Small%2C%20fringed%20flowers%20in%20dense%2C%20flat-topped%20clusters.%20%7C%0A%7C%20Sword%20Lily%20%7C%20*Gladiolus*%20%7C%20Tall%20spikes%20of%20ruffled%2C%20trumpet-shaped%20flowers.%20%7C%0A%7C%20Thorn%20Apple%20%7C%20*Datura%20stramonium*%20%7C%20Large%2C%20white%20upright%20trumpet%20flowers%20with%20spiky%20pods.%20%7C%0A%7C%20Wallflower%20%7C%20*Erysimum%20cheiri*%20%7C%20Fragrant%2C%20four-petaled%20flowers%20in%20warm%20earth%20tones.%20%7C

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
