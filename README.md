# UK wards hex cartogram (2024) non-contiguous

This sub-project aims to build a hex cartogram of 2024 UK wards similar to the effort to create [an MSOA cartogram by the House of Commons Library](https://github.com/houseofcommonslibrary/uk-hex-cartograms-noncontiguous/).

## Rules to guide layout

These are some things to keep in mind when designing the layout: 

1. Wards should be grouped by local authority district as a contiguous shape. In some places it may make sense to make a contiguous group of local authorities (e.g. Greater Manchester) but each local authority should also be contiguous within itself. In general, leaving gaps between local authority groups is better because the gaps can be used to make the overall map look more like the country as a whole. It also means that any future ward additions/removals will be easier to deal with as less of the map will need re-arranging. Having each local authority be contiguous makes it easier to extract local authority-specific cartograms in the future.
2. Try to keep local authorities with an overall shape the roughly resembles the real geography.
3. Any wards with compass directions (e.g. Droylsden East and Droylsden West) should be arranged in roughly the correct orientation.
4. Try to preserve familiar features from the real geography e.g. islands, estuaries, coastlines etc. This won't always be possible and approximations will need to be made but it can help people navigate the abstracted geography.


## Editing

To help break up the task into more manageable pieces, the full ward map has been broken up by region or nation. This makes smaller files that are easier to work on and different people can edit different regions with less fear of clashes.

* [E12000001 - North East](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson)
* [E12000002 - North West](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson)
* [E12000003 - Yorkshire and the Humber](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson)
* [E12000004 - East Midlands](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson)
* [E12000005 - West Midlands](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson)
* [E12000006 - East of England](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson)
* [E12000007 - London](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson)
* [E12000008 - South East](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson)
* [E12000009 - South West](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson)
* [N92000002 - Northern Ireland](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson)
* [S92000003 - Scotland](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson)
* [W92000004 - Wales](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson)

Please edit a region using the hex builder tool, save the output as HexJSON[^1], then over-write the appropriate file in this directory. 
The [full map](https://open-innovations.org/projects/hexmaps/editor/?../maps/uk-wards-2024.hexjson) will be created by combining each of the regions into a final HexJSON file.

The [Wards (May 2024) Boundaries UK SGC](https://geoportal.statistics.gov.uk/datasets/ons::wards-may-2024-boundaries-uk-bsc-2/explore) from the ONS is useful to see the geographic placement of wards. 

## Progress

This is a list of local authority districts and if their wards have been arranged:

- [ ] [E06000001](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Hartlepool
- [ ] [E06000002](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Middlesbrough
- [ ] [E06000003](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Redcar and Cleveland
- [ ] [E06000004](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Stockton-on-Tees
- [ ] [E06000005](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Darlington
- [ ] [E06000006](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Halton
- [ ] [E06000007](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Warrington
- [ ] [E06000008](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Blackburn with Darwen
- [ ] [E06000009](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Blackpool
- [ ] [E06000010](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Kingston upon Hull, City of
- [ ] [E06000011](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - East Riding of Yorkshire
- [ ] [E06000012](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - North East Lincolnshire
- [ ] [E06000013](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - North Lincolnshire
- [x] [E06000014](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - York (@slowe)
- [ ] [E06000015](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Derby
- [ ] [E06000016](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Leicester
- [ ] [E06000017](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Rutland
- [ ] [E06000018](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Nottingham
- [ ] [E06000019](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Herefordshire, County of
- [ ] [E06000020](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Telford and Wrekin
- [ ] [E06000021](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Stoke-on-Trent
- [ ] [E06000022](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Bath and North East Somerset
- [ ] [E06000023](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Bristol, City of
- [ ] [E06000024](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - North Somerset
- [ ] [E06000025](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - South Gloucestershire
- [ ] [E06000026](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Plymouth
- [ ] [E06000027](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Torbay
- [ ] [E06000030](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Swindon
- [ ] [E06000031](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Peterborough
- [ ] [E06000032](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Luton
- [ ] [E06000033](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Southend-on-Sea
- [ ] [E06000034](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Thurrock
- [ ] [E06000035](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Medway
- [ ] [E06000036](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Bracknell Forest
- [ ] [E06000037](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - West Berkshire
- [ ] [E06000038](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Reading
- [ ] [E06000039](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Slough
- [ ] [E06000040](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Windsor and Maidenhead
- [ ] [E06000041](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Wokingham
- [ ] [E06000042](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Milton Keynes
- [ ] [E06000043](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Brighton and Hove
- [ ] [E06000044](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Portsmouth
- [ ] [E06000045](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Southampton
- [ ] [E06000046](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Isle of Wight
- [ ] [E06000047](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - County Durham
- [ ] [E06000049](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Cheshire East
- [ ] [E06000050](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Cheshire West and Chester
- [ ] [E06000051](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Shropshire
- [ ] [E06000052](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Cornwall
- [ ] [E06000053](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Isles of Scilly
- [ ] [E06000054](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Wiltshire
- [ ] [E06000055](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Bedford
- [ ] [E06000056](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Central Bedfordshire
- [ ] [E06000057](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Northumberland
- [ ] [E06000058](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Bournemouth, Christchurch and Poole
- [ ] [E06000059](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Dorset
- [ ] [E06000060](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Buckinghamshire
- [ ] [E06000061](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - North Northamptonshire
- [ ] [E06000062](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - West Northamptonshire
- [ ] [E06000063](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Cumberland
- [ ] [E06000064](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Westmorland and Furness
- [ ] [E06000065](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - North Yorkshire
- [ ] [E06000066](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Somerset
- [ ] [E07000008](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Cambridge
- [ ] [E07000009](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - East Cambridgeshire
- [ ] [E07000010](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Fenland
- [ ] [E07000011](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Huntingdonshire
- [ ] [E07000012](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - South Cambridgeshire
- [ ] [E07000032](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Amber Valley
- [ ] [E07000033](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Bolsover
- [ ] [E07000034](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Chesterfield
- [ ] [E07000035](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Derbyshire Dales
- [ ] [E07000036](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Erewash
- [ ] [E07000037](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - High Peak
- [ ] [E07000038](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - North East Derbyshire
- [ ] [E07000039](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - South Derbyshire
- [ ] [E07000040](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - East Devon
- [ ] [E07000041](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Exeter
- [ ] [E07000042](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Mid Devon
- [ ] [E07000043](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - North Devon
- [ ] [E07000044](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - South Hams
- [ ] [E07000045](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Teignbridge
- [ ] [E07000046](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Torridge
- [ ] [E07000047](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - West Devon
- [ ] [E07000061](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Eastbourne
- [ ] [E07000062](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Hastings
- [ ] [E07000063](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Lewes
- [ ] [E07000064](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Rother
- [ ] [E07000065](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Wealden
- [ ] [E07000066](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Basildon
- [ ] [E07000067](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Braintree
- [ ] [E07000068](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Brentwood
- [ ] [E07000069](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Castle Point
- [ ] [E07000070](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Chelmsford
- [ ] [E07000071](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Colchester
- [ ] [E07000072](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Epping Forest
- [ ] [E07000073](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Harlow
- [ ] [E07000074](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Maldon
- [ ] [E07000075](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Rochford
- [ ] [E07000076](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Tendring
- [ ] [E07000077](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Uttlesford
- [ ] [E07000078](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Cheltenham
- [ ] [E07000079](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Cotswold
- [ ] [E07000080](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Forest of Dean
- [ ] [E07000081](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Gloucester
- [ ] [E07000082](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Stroud
- [ ] [E07000083](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000009.hexjson) - Tewkesbury
- [ ] [E07000084](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Basingstoke and Deane
- [ ] [E07000085](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - East Hampshire
- [ ] [E07000086](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Eastleigh
- [ ] [E07000087](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Fareham
- [ ] [E07000088](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Gosport
- [ ] [E07000089](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Hart
- [ ] [E07000090](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Havant
- [ ] [E07000091](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - New Forest
- [ ] [E07000092](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Rushmoor
- [ ] [E07000093](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Test Valley
- [ ] [E07000094](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Winchester
- [ ] [E07000095](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Broxbourne
- [ ] [E07000096](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Dacorum
- [ ] [E07000098](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Hertsmere
- [ ] [E07000099](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - North Hertfordshire
- [ ] [E07000102](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Three Rivers
- [ ] [E07000103](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Watford
- [ ] [E07000105](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Ashford
- [ ] [E07000106](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Canterbury
- [ ] [E07000107](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Dartford
- [ ] [E07000108](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Dover
- [ ] [E07000109](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Gravesham
- [ ] [E07000110](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Maidstone
- [ ] [E07000111](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Sevenoaks
- [ ] [E07000112](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Folkestone and Hythe
- [ ] [E07000113](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Swale
- [ ] [E07000114](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Thanet
- [ ] [E07000115](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Tonbridge and Malling
- [ ] [E07000116](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Tunbridge Wells
- [ ] [E07000117](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Burnley
- [ ] [E07000118](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Chorley
- [ ] [E07000119](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Fylde
- [ ] [E07000120](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Hyndburn
- [ ] [E07000121](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Lancaster
- [ ] [E07000122](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Pendle
- [ ] [E07000123](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Preston
- [ ] [E07000124](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Ribble Valley
- [x] [E07000125](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Rossendale (@slowe)
- [ ] [E07000126](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - South Ribble
- [ ] [E07000127](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - West Lancashire
- [ ] [E07000128](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Wyre
- [ ] [E07000129](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Blaby
- [ ] [E07000130](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Charnwood
- [ ] [E07000131](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Harborough
- [ ] [E07000132](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Hinckley and Bosworth
- [ ] [E07000133](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Melton
- [ ] [E07000134](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - North West Leicestershire
- [ ] [E07000135](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Oadby and Wigston
- [ ] [E07000136](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Boston
- [ ] [E07000137](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - East Lindsey
- [ ] [E07000138](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Lincoln
- [ ] [E07000139](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - North Kesteven
- [ ] [E07000140](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - South Holland
- [ ] [E07000141](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - South Kesteven
- [ ] [E07000142](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - West Lindsey
- [ ] [E07000143](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Breckland
- [ ] [E07000144](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Broadland
- [ ] [E07000145](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Great Yarmouth
- [ ] [E07000146](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - King's Lynn and West Norfolk
- [ ] [E07000147](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - North Norfolk
- [ ] [E07000148](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Norwich
- [ ] [E07000149](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - South Norfolk
- [ ] [E07000170](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Ashfield
- [ ] [E07000171](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Bassetlaw
- [ ] [E07000172](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Broxtowe
- [ ] [E07000173](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Gedling
- [ ] [E07000174](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Mansfield
- [ ] [E07000175](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Newark and Sherwood
- [ ] [E07000176](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000004.hexjson) - Rushcliffe
- [ ] [E07000177](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Cherwell
- [ ] [E07000178](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Oxford
- [ ] [E07000179](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - South Oxfordshire
- [ ] [E07000180](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Vale of White Horse
- [ ] [E07000181](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - West Oxfordshire
- [ ] [E07000192](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Cannock Chase
- [ ] [E07000193](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - East Staffordshire
- [ ] [E07000194](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Lichfield
- [ ] [E07000195](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Newcastle-under-Lyme
- [ ] [E07000196](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - South Staffordshire
- [ ] [E07000197](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Stafford
- [ ] [E07000198](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Staffordshire Moorlands
- [ ] [E07000199](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Tamworth
- [ ] [E07000200](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Babergh
- [ ] [E07000202](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Ipswich
- [ ] [E07000203](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Mid Suffolk
- [ ] [E07000207](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Elmbridge
- [ ] [E07000208](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Epsom and Ewell
- [ ] [E07000209](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Guildford
- [ ] [E07000210](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Mole Valley
- [ ] [E07000211](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Reigate and Banstead
- [ ] [E07000212](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Runnymede
- [ ] [E07000213](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Spelthorne
- [ ] [E07000214](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Surrey Heath
- [ ] [E07000215](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Tandridge
- [ ] [E07000216](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Waverley
- [ ] [E07000217](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Woking
- [ ] [E07000218](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - North Warwickshire
- [ ] [E07000219](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Nuneaton and Bedworth
- [ ] [E07000220](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Rugby
- [ ] [E07000221](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Stratford-on-Avon
- [ ] [E07000222](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Warwick
- [ ] [E07000223](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Adur
- [ ] [E07000224](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Arun
- [ ] [E07000225](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Chichester
- [ ] [E07000226](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Crawley
- [ ] [E07000227](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Horsham
- [ ] [E07000228](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Mid Sussex
- [ ] [E07000229](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000008.hexjson) - Worthing
- [ ] [E07000234](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Bromsgrove
- [ ] [E07000235](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Malvern Hills
- [ ] [E07000236](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Redditch
- [ ] [E07000237](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Worcester
- [ ] [E07000238](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Wychavon
- [ ] [E07000239](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Wyre Forest
- [ ] [E07000240](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - St Albans
- [ ] [E07000241](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Welwyn Hatfield
- [ ] [E07000242](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - East Hertfordshire
- [ ] [E07000243](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - Stevenage
- [ ] [E07000244](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - East Suffolk
- [ ] [E07000245](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000006.hexjson) - West Suffolk
- [ ] [E08000001](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Bolton
- [ ] [E08000002](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Bury
- [x] [E08000003](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Manchester (@slowe)
- [x] [E08000004](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Oldham (@slowe)
- [ ] [E08000005](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Rochdale
- [ ] [E08000006](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Salford
- [ ] [E08000007](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Stockport
- [ ] [E08000008](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Tameside
- [ ] [E08000009](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Trafford
- [ ] [E08000010](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Wigan
- [ ] [E08000011](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Knowsley
- [ ] [E08000012](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Liverpool
- [ ] [E08000013](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - St. Helens
- [ ] [E08000014](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Sefton
- [ ] [E08000015](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000002.hexjson) - Wirral
- [ ] [E08000016](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Barnsley
- [ ] [E08000017](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Doncaster
- [ ] [E08000018](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Rotherham
- [ ] [E08000019](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Sheffield
- [ ] [E08000021](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Newcastle upon Tyne
- [ ] [E08000022](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - North Tyneside
- [ ] [E08000023](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - South Tyneside
- [ ] [E08000024](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Sunderland
- [ ] [E08000025](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Birmingham
- [ ] [E08000026](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Coventry
- [ ] [E08000027](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Dudley
- [ ] [E08000028](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Sandwell
- [ ] [E08000029](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Solihull
- [ ] [E08000030](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Walsall
- [ ] [E08000031](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000005.hexjson) - Wolverhampton
- [x] [E08000032](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Bradford (@slowe)
- [x] [E08000033](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Calderdale (@slowe)
- [x] [E08000034](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Kirklees (@slowe)
- [x] [E08000035](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Leeds (@slowe)
- [x] [E08000036](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000003.hexjson) - Wakefield (@slowe)
- [ ] [E08000037](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000001.hexjson) - Gateshead
- [ ] [E09000001](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - City of London
- [ ] [E09000002](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Barking and Dagenham
- [ ] [E09000003](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Barnet
- [ ] [E09000004](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Bexley
- [ ] [E09000005](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Brent
- [ ] [E09000006](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Bromley
- [ ] [E09000007](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Camden
- [ ] [E09000008](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Croydon
- [ ] [E09000009](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Ealing
- [ ] [E09000010](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Enfield
- [ ] [E09000011](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Greenwich
- [ ] [E09000012](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Hackney
- [ ] [E09000013](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Hammersmith and Fulham
- [ ] [E09000014](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Haringey
- [ ] [E09000015](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Harrow
- [ ] [E09000016](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Havering
- [ ] [E09000017](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Hillingdon
- [ ] [E09000018](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Hounslow
- [ ] [E09000019](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Islington
- [ ] [E09000020](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Kensington and Chelsea
- [ ] [E09000021](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Kingston upon Thames
- [ ] [E09000022](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Lambeth
- [ ] [E09000023](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Lewisham
- [ ] [E09000024](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Merton
- [ ] [E09000025](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Newham
- [ ] [E09000026](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Redbridge
- [ ] [E09000027](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Richmond upon Thames
- [ ] [E09000028](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Southwark
- [ ] [E09000029](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Sutton
- [ ] [E09000030](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Tower Hamlets
- [ ] [E09000031](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Waltham Forest
- [ ] [E09000032](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Wandsworth
- [ ] [E09000033](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/E12000007.hexjson) - Westminster
- [ ] [N09000001](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Antrim and Newtownabbey
- [ ] [N09000002](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Armagh City, Banbridge and Craigavon
- [ ] [N09000003](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Belfast
- [ ] [N09000004](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Causeway Coast and Glens
- [ ] [N09000005](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Derry City and Strabane
- [ ] [N09000006](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Fermanagh and Omagh
- [ ] [N09000007](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Lisburn and Castlereagh
- [ ] [N09000008](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Mid and East Antrim
- [ ] [N09000009](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Mid Ulster
- [ ] [N09000010](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Newry, Mourne and Down
- [ ] [N09000011](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/N92000002.hexjson) - Ards and North Down
- [ ] [S12000005](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Clackmannanshire
- [ ] [S12000006](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Dumfries and Galloway
- [ ] [S12000008](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - East Ayrshire
- [ ] [S12000010](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - East Lothian
- [ ] [S12000011](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - East Renfrewshire
- [ ] [S12000013](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Na h-Eileanan Siar
- [ ] [S12000014](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Falkirk
- [ ] [S12000017](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Highland
- [ ] [S12000018](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Inverclyde
- [ ] [S12000019](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Midlothian
- [ ] [S12000020](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Moray
- [ ] [S12000021](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - North Ayrshire
- [ ] [S12000023](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Orkney Islands
- [ ] [S12000026](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Scottish Borders
- [ ] [S12000027](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Shetland Islands
- [ ] [S12000028](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - South Ayrshire
- [ ] [S12000029](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - South Lanarkshire
- [ ] [S12000030](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Stirling
- [ ] [S12000033](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Aberdeen City
- [ ] [S12000034](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Aberdeenshire
- [ ] [S12000035](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Argyll and Bute
- [ ] [S12000036](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - City of Edinburgh
- [ ] [S12000038](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Renfrewshire
- [ ] [S12000039](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - West Dunbartonshire
- [ ] [S12000040](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - West Lothian
- [ ] [S12000041](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Angus
- [ ] [S12000042](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Dundee City
- [ ] [S12000045](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - East Dunbartonshire
- [ ] [S12000047](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Fife
- [ ] [S12000048](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Perth and Kinross
- [ ] [S12000049](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - Glasgow City
- [ ] [S12000050](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/S92000003.hexjson) - North Lanarkshire
- [ ] [W06000001](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Isle of Anglesey
- [ ] [W06000002](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Gwynedd
- [ ] [W06000003](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Conwy
- [ ] [W06000004](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Denbighshire
- [ ] [W06000005](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Flintshire
- [ ] [W06000006](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Wrexham
- [ ] [W06000008](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Ceredigion
- [ ] [W06000009](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Pembrokeshire
- [ ] [W06000010](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Carmarthenshire
- [ ] [W06000011](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Swansea
- [ ] [W06000012](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Neath Port Talbot
- [ ] [W06000013](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Bridgend
- [ ] [W06000014](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Vale of Glamorgan
- [ ] [W06000015](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Cardiff
- [ ] [W06000016](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Rhondda Cynon Taf
- [ ] [W06000018](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Caerphilly
- [ ] [W06000019](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Blaenau Gwent
- [ ] [W06000020](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Torfaen
- [ ] [W06000021](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Monmouthshire
- [ ] [W06000022](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Newport
- [ ] [W06000023](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Powys
- [ ] [W06000024](https://open-innovations.org/projects/hexmaps/editor/?https://open-innovations.github.io/uk-wards-2024/W92000004.hexjson) - Merthyr Tydfil

[^1]: [HexJSON](https://open-innovations.org/projects/hexmaps/hexjson) is a simple text-based file format for sharing hex layouts. 
