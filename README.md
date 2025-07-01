## amazon-arts-crafts-reviews-topic-modeling-python
In this project, I conducted topic modeling using Latent Semantic Analysis and Latent Dirichlet Allocation methods on an Amazon Arts, Crafts, and Sewing review dataset containing more than 100,000 product reviews, aiming to uncover valuable insights from unstructured customer feedback. 

## 📘 Notebook
You can view the full code and analysis in [AmazonTextMiningProject.ipynb](./AmazonTextMiningProject.ipynb)

## Comparison of the LSA and LDA Results - Patterns, Insights

1. Topic Comparisons between LSA and LDA:

+ Topic 1 from the LSA model and Topics 1 and 2 from the LDA model both contain key words that I thought related to general product satisfaction and versatility.
+ Topic 2 from the LSA model and Topic 2 from the LDA model both show how the words "sewing" and "machine" are commonly used together.
+ Topic 3 from the LSA model and Topic 0 from the LDA model both seem like they emphasize product value and quality.
+ Topic 4 from the LSA model and Topic 3 from the LDA model both mention words that relate to crafting tools and accessories.
+ Topic 5 from the LSA model and Topics 2 and 4 from the LDA model both focus on yarn-related hobbies like knitting and crochet for  the theme. 

2. Key Patterns and Insights:
Overall, I found that both models generated themes with words that mention specific tools including machines, threads, and blades, which shows that amazon reviews for arts, crafts, and sewing are generally focused on the product-specific feedback. Additionally, words that show sentiment such as "love" and "great" appear prevalently across the topics, which tells me that the arts and crafts product reviews are generally positive. I also noticed that words only relating to knitting and crochet were prevalent enough to be formed into a topic on their own, so this means that knitting and crocheting products are very commonly reviewed. Finally, LDA Topic 0 and 4 both mention colors and words that describe colors, which I think shows that people who are reviewing these types of items care a lot about aesthetics.
