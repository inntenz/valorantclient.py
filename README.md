# valorantclient.py

### API wrapper for VALORANT's client API



## Installation
```python
pip install intenzclient
```

## Example

```python
from intenzclient import Client

client = Client(region="eu")
client.activate()

print(client.fetch_account_xp())
```

## Notes
- don't use this to make anything that's obviously against TOS (i.e. automatic agent selecting program)
- just don't be dumb :)



