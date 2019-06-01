## Quality-of-products-from-user-reviews
# Does higher quality mean higher price? Some evidence from scraped data

Several important predictions produced by theoretical literature on product differentiation can hardly be tested due to the lack of data. In particular, the empirical researchers seldom have a good measure of product *quality*, since most data come from customs records. Most empirical research so far has used data on *prices* to obtain quality ranking of products (see e.g. Kugler & Verhoogen, 2011; Manova & Zhang, 2012). Say, we have customs data (prices and volumes) on a narrowly defined product (i.e. waterproof watches, milk chocolate with almonds, etc.). Then products within a given product category with higher price are typically assumed to be the products of higher quality. Intuitively, if quality were low, producers wouldn't be able to charge higher prices. If quality of a product falls, so should the demand for it and, in turn, its price. This assumption is often taken in the empirical research and cannot be assessed with the customs data.

Data collected from the web make it possible to assess this assumption. Price comparison services contain information on prices and have a good proxy for quality - user rating. https://classic.prisjakt.nu/ turns out to be a good source of these data, as users rate the products and not the sellers. The obvious caveat with using rating data as a proxy for quality is that different users put different weights on various characteristics of the products. Next, there is certainly self-selection in the process of rating a product. I ignore these issues at this stage and focus on the technical side of data collection - scraping - as a potential tool for advancing our understanding of theoretical proedictions. I also provide some basic analysis of the relationship of interest.

The results reveal that while for some products the correlation is indeed positive and statistically significant, some products exhibit a negative correlation between price and user rating. One possible explanation of this
finding is the importance of horizontal differentiation. Horizontal differentiation refers to differences in
products that cannot be easily evaluated in terms of quality. In fact, the theoretical assumption about the
positive correlation between price and quality should hold for a narrowly defined product category, that is for
the products with relatively few characteristics. Products with fewer characteristics are more easily
comparable to each other. Hence, user ratings should have less dimensions of comparison. Indeed, such
products as kitchen blenders and wireless headphones have the correlation coefficient 0.45 and 0.39
correspondingly. More complex products (with regards to the amount of product characteristics available to
choose from) such as stroller och photo camera, exhibit negative correlation between price and rating
(-0.11). Another explanation of the negative correlation could be that the newest models of products tend to
be more expensive, whereas they might still have less reviews by users.
Overall, to test the assumption, a more nuanced research design is needed. Without accounting for selfselection,
horizontal differentiation and novelty of product announcements, the analysis casts some doubts
on the assumption of strong positive correlation between prices and quality.

*References:*
 - Kugler, Maurice, and Eric Verhoogen. "Prices, plant size, and product quality." The Review of Economic Studies 79.1 (2011): 307-339. \n
 - Manova, Kalina, and Zhiwei Zhang. "Export prices across firms and destinations." The Quarterly Journal of Economics 127.1 (2012): 379-436.
