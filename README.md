# Normalizing-flows-for-Phantom---Real-CT-mapping

Ideas

1. Each pixel intensity = dimension → each image = a point on the [image width x length] vector space → get a distribution from image samples → apply a flow model to the distributions directly
2. Train a model in such a way that X → Y mapping in a latent space can be represented by adding a normaly distributed parameter
3. Phantom → Distribution_1, CT scan → Distribution_2, Distribution_1 → CT scan. All three models are invertible
