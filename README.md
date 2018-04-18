# to use
-------
- eth mining
```
docker-compose up -d
docker attach dockerethereum_eth_1
eth -a 0x49Ed989fF5D7B58D81ea76FDC043a9990778e17D -C -m on -t 32
docker attach dockerethereum_gethconsole_1
geth --mine --etherbase 0x49Ed989fF5D7B58D81ea76FDC043a9990778e17D --gasprice "20000000000" --minerthreads 32
```

## Ref
- [Original](README-orig.md) README
- donation ETH: 0x49Ed989fF5D7B58D81ea76FDC043a9990778e17D
