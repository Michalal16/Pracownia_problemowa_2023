# Analiza ruchu sieciowego TCP/IP i wykrywanie anomalii w tym ruchu spowodowanym atakiem z zewnątrz

## Typ ataku - DDos

## Dataset
    Dane uczące - https://www.kaggle.com/datasets/amanverma1999/a-comprehensive-dataset-for-ddos-attack/code
    Dane testowe - https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection/code?fbclid=IwAR23kkptP0iMuFmPxALbx2IKxlV0x32RTCnccDECaokPVA8hsouyU6RDH44

## Utworzenie zbioru uczącego i testowego
    - Ze względu na fakt że zbiór uczący z network-intrusion-detection nie zawiera informacji o rodzaju ataktu DDos zbiór uczący został wykorzystany z a-comprehensive-dataset-for-ddos-attack.
    - Dane w zbiorze uczącym zostały przefiltrowany ze względu na ataki oparte o protół TCP - UDP odrzucone.
    - Sprawdzenie czy zbiór nie posiada duplikatów i usuniecie ich.
    