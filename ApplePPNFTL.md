ApplePPNFTL is the first FTL driver introduced for PPN devices. It uses [YaFTL](YaFTL.md) on top of a [PPNVFL](PPNVFL.md) layer. It is unclear whether this FTL has been used on production devices : it is present in the iOS 4.1 kernelcache but replaced and referred  to as "vanilla" by [AppleSwissPPNFTL](AppleSwissPPNFTL.md) in iOS 5.