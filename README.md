# AsyncEtherScanApis
# support
```
python 3.7.3 +
aiohttp 3.0 +
```

# use:
```python
from etherscan import EtherScan
async def main():
       f = EtherScan(api_key="{token}")
        await f.open_session() # or Etherscan(api_key="{token}",session)
        print(await f.your_method())
asyncio.run(main())
```
