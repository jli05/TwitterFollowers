# Shopifty Twitter Programming Test

We identify the common followers of @Shopify and @ShopifyPicks. The solution notebook is `ShopifyTest.ipynb`. We stored the IDs of the two follower lists of @Shopify and @ShopifyPicks in `twitter-followers.npy`. 

```python
[Shopify_followers_ids, Shopify_Picks_followers_ids] = numpy.load('twitter-followers.npy')
```

The common follower IDs and their names of both @Shopify and @ShopifyPicks are stored in `common-followers.npy`.

```python
[common_followers, common_follower_names] = numpy.load('common-followers.npy')
```
