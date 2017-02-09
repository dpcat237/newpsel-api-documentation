Method syncs tags.

Changes processes:
- If tag doesn't have tag_id, it will be created in the data base.
- If tag which came from a device has newer date than in data base, this tag name will be update from the device.
- If tag exists in the data base but tag's name from device is empty, tag and related saved articles will be deleted.
