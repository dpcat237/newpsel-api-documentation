Method returns saved articles.

Variables description:
- "saved_articles": list of IDs of articles which exist in the device.
- "tags": list of tags IDs associated with saved article.


Changes processes:
- If associated tag doesn't exist in the data bases, will be created the association.
- If the association exists in the data base but didn't come from the device, saved article will be marked as reading.
