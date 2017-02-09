Method syncs tags.

Changes processes:
- If the tag doesn't have tag_id, it will be created in the database.
- If tag which came from a device has a newer date than in the database, this tag name will be updated from the device.
- If the tag exists in the database but tag's name from the device is empty, the tag will be deleted along with his related saved articles.
