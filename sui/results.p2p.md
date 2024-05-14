These are the results of running `sui/p2p_transfer/index.js`.

### Running the original code

Average time:
`1.004169935 seconds`

Script output:
```
E2E latency for p2p transfer: 1.297151333 s
E2E latency for p2p transfer: 1.041882917 s
E2E latency for p2p transfer: 1.1213525420000006 s
E2E latency for p2p transfer: 0.8823682090000002 s
E2E latency for p2p transfer: 1.0141877079999995 s
E2E latency for p2p transfer: 0.9412166249999991 s
E2E latency for p2p transfer: 0.9615968749999992 s
E2E latency for p2p transfer: 0.9282431669999988 s
E2E latency for p2p transfer: 0.9637725419999988 s
E2E latency for p2p transfer: 1.1034594580000012 s
E2E latency for p2p transfer: 0.9562152080000015 s
E2E latency for p2p transfer: 0.9088973750000005 s
E2E latency for p2p transfer: 0.9724023750000015 s
E2E latency for p2p transfer: 0.965632749999997 s
```

### CHANGE 1: You already know how much the iPhone costs, no need to ask the clerk

```
txb.setGasBudget(1000000);
```

Average time:
`0.8944658776 seconds`

Script output:
```
E2E latency for p2p transfer: 1.218643541 s
E2E latency for p2p transfer: 0.9281938340000001 s
E2E latency for p2p transfer: 0.8496001249999999 s
E2E latency for p2p transfer: 0.9377642079999996 s
E2E latency for p2p transfer: 0.842752375 s
E2E latency for p2p transfer: 0.8395727499999993 s
E2E latency for p2p transfer: 0.8411905000000006 s
E2E latency for p2p transfer: 0.9533147919999992 s
E2E latency for p2p transfer: 0.9047976669999989 s
E2E latency for p2p transfer: 0.8714824159999989 s
E2E latency for p2p transfer: 0.9400831670000007 s
E2E latency for p2p transfer: 0.8175947500000003 s
E2E latency for p2p transfer: 0.810559541999999 s
E2E latency for p2p transfer: 0.8865039580000011 s
E2E latency for p2p transfer: 0.8164212499999994 s
E2E latency for p2p transfer: 0.8529791669999977 s
```
