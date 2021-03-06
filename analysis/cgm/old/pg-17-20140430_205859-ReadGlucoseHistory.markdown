## do stuff with an insulin pump over RF
using ` Namespace(begin=None, bytesPerRecord=None, command='tweak', descr=None, dryrun=False, effectTime=None, end=None, init=True, maxRecords=None, name=None, no_postlude=False, no_prelude=False, no_rf_prelude=False, other='ReadGlucoseHistory', page=17, params=None, port='/dev/ttyUSB0', postfix=None, prefix=None, prefix_path='logs/20140430_205859-', save=True, saveall=False, serial='584923', verbose=None) `
```
```
```
```
```
```
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 0L,
           'packets.transmit': 0L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 22L,
         'packets.transmit': 22L}}
```
```
PowerControl SERIAL 584923
```
### PUMP MODEL: `ReadPumpModel:size[64]:data:'722'`
<class 'decocare.commands.ReadGlucoseHistory'> {'page': 17}
response: ReadGlucoseHistory:size[1024]:[page][0]:data[1024]:
hexdump:
```python
0000   0x40 0x40 0x41 0x13 0x42 0x13 0x46 0x4a    @@A.B.FJ
0008   0x13 0x4c 0x13 0x4e 0x13 0x4f 0x13 0x50    .L.N.O.P
0010   0x13 0x51 0x13 0x52 0x0e 0x5a 0x05 0x40    .Q.R.Z.@
0018   0x08 0x13 0x53 0x54 0x13 0x55 0x13 0x55    ..ST.U.U
0020   0x53 0x53 0x52 0x52 0x51 0x51 0x51 0x51    SSRRQQQQ
0028   0x54 0x5e 0x65 0x6a 0x6c 0x6e 0x6e 0x6f    T^ejlnno
0030   0x70 0x71 0x71 0x72 0x73 0x73 0x75 0x76    pqqrssuv
0038   0x72 0x6e 0x6a 0x69 0x68 0x66 0x64 0x60    rnjihfd`
0040   0x5e 0x5a 0x5d 0x67 0x6e 0x71 0x72 0x73    ^Z]gnqrs
0048   0x73 0x74 0x74 0x73 0x74 0x74 0x74 0x74    sttstttt
0050   0x73 0x73 0x73 0x71 0x6d 0x69 0x66 0x65    sssqmife
0058   0x6b 0x70 0x72 0x71 0x70 0x70 0x6f 0x70    kprqppop
0060   0x71 0x73 0x70 0x6c 0x68 0x65 0x63 0x62    qsplhecb
0068   0x61 0x60 0x5f 0x61 0x63 0x69 0x6d 0x6c    a`_aciml
0070   0x69 0x68 0x6c 0x13 0x72 0x74 0x74 0x76    ihl.rttv
0078   0x77 0x76 0x76 0x7a 0x7e 0x0e 0x5a 0x05    wvvz~.Z.
0080   0x48 0x08 0x0e 0x1a 0x0a 0x48 0x0b 0x0e    H....H..
0088   0x3a 0x0a 0x48 0x0b 0x0e 0x3a 0x0b 0x48    :.H..:.H
0090   0x0d 0x00 0x03 0xe7 0x0e 0x1a 0x0c 0x48    .......H
0098   0x0e 0x13 0x02 0x0e 0x5a 0x0f 0x48 0x08    ....Z.H.
00A0   0x0e 0x1a 0x14 0x48 0x0b 0x0e 0x3a 0x14    ...H..:.
00A8   0x48 0x0b 0x0e 0x3a 0x14 0x48 0x0d 0x01    H..:.H..
00B0   0x03 0xe6 0x0e 0x1a 0x17 0x48 0x0e 0xe7    .....H..
00B8   0x0e 0x1a 0x19 0x48 0x0e 0x01 0x03 0x01    ...H....
00C0   0x03 0x73 0xef 0x11 0x0e 0x1a 0x23 0x48    .s....#H
00C8   0x0f 0xe2 0x0e 0x1a 0x25 0x48 0x0e 0x70    ....%H.p
00D0   0x6c 0x6c 0x93 0x12 0x0e 0x1a 0x33 0x48    ll....3H
00D8   0x0f 0x69 0x65 0x61 0x5c 0x59 0x59 0x59    .iea\YYY
00E0   0x57 0x51 0x4b 0x47 0x43 0x42 0x42 0x43    WQKGCBBC
00E8   0x44 0x44 0x44 0x44 0x44 0x43 0x42 0x3f    DDDDDCB?
00F0   0x40 0x42 0x44 0x45 0x45 0x46 0x47 0x48    @BDEEFGH
00F8   0x4a 0x4c 0xa2 0x0e 0x1a 0x26 0x4b 0x0e    JL...&K.
0100   0x4f 0x55 0x57 0xe5 0x11 0x0e 0x1a 0x32    OUW....2
0108   0x4b 0x0f 0x5b 0x5c 0x5b 0x59 0x57 0x57    K.[\[YWW
0110   0x59 0x5c 0x5b 0x58 0x54 0x52 0x51 0x50    Y\[XTRQP
0118   0x4f 0x4f 0x50 0x50 0x51 0x52 0x53 0x56    OOPPQRSV
0120   0x59 0x5a 0x5a 0x59 0x58 0x57 0x56 0x58    YZZYXWVX
0128   0x59 0x5b 0x5e 0x61 0x64 0x66 0x68 0x69    Y[^adfhi
0130   0x6b 0x6a 0x6a 0x6b 0x6d 0x6e 0x70 0x73    kjjkmnps
0138   0x0e 0x1a 0x28 0x4f 0x08 0x75 0x77 0x79    ..(O.uwy
0140   0x79 0x79 0x7a 0x7e 0x82 0x85 0x87 0x86    yyz~....
0148   0x04 0x0e 0x3a 0x27 0x50 0x0e 0x04 0x0e    ..:'P...
0150   0x3a 0x28 0x50 0x0e 0x85 0x04 0x0e 0x3a    :(P....:
0158   0x29 0x50 0x0e 0x04 0x0e 0x3a 0x2d 0x50    )P...:-P
0160   0x0e 0x13 0x83 0x04 0x0e 0x3a 0x32 0x50    .....:2P
0168   0x0e 0x83 0x04 0x0e 0x3a 0x33 0x50 0x0e    ....:3P.
0170   0x04 0x0e 0x3a 0x35 0x50 0x0e 0x84 0x86    ..:5P...
0178   0xfa 0x0e 0x1a 0x04 0x51 0x0e 0xfa 0x0e    ....Q...
0180   0x1a 0x05 0x51 0x0e 0x87 0x88 0x81 0x07    ..Q.....
0188   0x11 0x0e 0x1a 0x0f 0x51 0x0f 0x80 0x13    ....Q...
0190   0x7f 0x13 0x7d 0x13 0x7a 0x13 0x78 0x13    ..}.z.x.
0198   0x76 0x13 0x73 0x71 0x70 0x71 0x75 0x77    v.sqpquw
01A0   0x0e 0x1a 0x0f 0x52 0x08 0x78 0x77 0x76    ...R.xwv
01A8   0x74 0x72 0x70 0x07 0x0e 0x3a 0x30 0x52    trp..:0R
01B0   0x0e 0x6c 0x65 0x6b 0x24 0x13 0x0e 0x1a    .lek$...
01B8   0x00 0x53 0x0f 0x65 0x60 0x5a 0x55 0x51    .S.e`ZUQ
01C0   0x4e 0x4b 0x49 0x48 0x47 0x48 0x47 0x46    NKIHGHGF
01C8   0x46 0x47 0x49 0x4c 0x4e 0x4f 0x4f 0x50    FGILNOOP
01D0   0x51 0x51 0x4f 0x4c 0x89 0x0e 0x1a 0x09    QQOL....
01D8   0x55 0x0e 0x4a 0x47 0x44 0x25 0x13 0x0e    U.JGD%..
01E0   0x1a 0x14 0x55 0x0f 0x41 0x3d 0x3a 0x37    ..U.A=:7
01E8   0x36 0x36 0x37 0x38 0x38 0x38 0x39 0x39    66788899
01F0   0x39 0x39 0x39 0x38 0x36 0x35 0x0e 0x1a    999865..
01F8   0x32 0x56 0x08 0x0e 0x1a 0x32 0x56 0x08    2V...2V.
0200   0x33 0x32 0x0e 0x1a 0x00 0x57 0x08 0x0e    32...W..
0208   0x1a 0x00 0x57 0x08 0x31 0x0e 0x1a 0x05    ..W.1...
0210   0x57 0x08 0x0e 0x1a 0x05 0x57 0x08 0x0e    W....W..
0218   0x1a 0x05 0x57 0x08 0x0e 0x1a 0x05 0x57    ..W....W
0220   0x08 0x31 0x30 0x30 0x2f 0x0e 0x1a 0x19    .100/...
0228   0x57 0x08 0x2d 0x2b 0x2b 0x2d 0x32 0x39    W.-++-29
0230   0x7d 0x0e 0x1a 0x39 0x57 0x0e 0x40 0x46    }..9W.@F
0238   0x49 0x70 0x12 0x0e 0x1b 0x0b 0x40 0x0f    Ip....@.
0240   0x49 0x48 0x48 0x47 0x44 0x42 0x40 0x40    IHHGDB@@
0248   0x42 0x42 0x42 0x42 0x42 0x42 0x43 0x43    BBBBBBCC
0250   0x43 0x43 0x43 0x42 0x41 0x41 0x40 0x40    CCCBAA@@
0258   0x40 0x3f 0x3f 0x3f 0x3f 0x3e 0x3e 0x3e    @????>>>
0260   0x3e 0x3e 0x3d 0x3d 0x3c 0x3c 0x3b 0x39    >>==<<;9
0268   0x37 0x36 0x35 0x34 0x33 0x33 0x32 0x33    76543323
0270   0x35 0x36 0x36 0x36 0x36 0x35 0x34 0x33    56666543
0278   0x32 0x31 0x30 0x30 0x2f 0x2f 0x30 0x31    2100//01
0280   0x31 0x32 0x32 0x32 0x33 0x33 0x34 0x34    12223344
0288   0x34 0x34 0x34 0x35 0x33 0x30 0x2e 0x2d    444530.-
0290   0x13 0x2c 0x2e 0x30 0x30 0x2f 0x30 0x31    .,.00/01
0298   0x32 0x32 0x33 0x33 0x32 0x13 0x31 0x31    22332.11
02A0   0x48 0x0e 0x1b 0x02 0x48 0x0e 0x33 0x34    H...H.34
02A8   0x30 0x7e 0x10 0x0e 0x1b 0x10 0x48 0x0f    0~....H.
02B0   0x33 0x38 0x3c 0x41 0x45 0x49 0x4d 0x50    38<AEIMP
02B8   0x51 0x50 0x98 0x0e 0x1b 0x07 0x49 0x0e    QP....I.
02C0   0x4f 0x50 0x4a 0x2c 0x0f 0x0e 0x1b 0x14    OPJ,....
02C8   0x49 0x0f 0x4a 0x4b 0x4e 0x52 0x56 0x58    I.JKNRVX
02D0   0x5b 0x5d 0x5d 0x5f 0x60 0x60 0x61 0x62    []]_``ab
02D8   0x65 0x67 0x65 0x61 0x5e 0x5a 0x58 0x56    egea^ZXV
02E0   0x55 0x54 0x53 0x54 0x55 0x53 0x52 0x53    UTSTUSRS
02E8   0x55 0x13 0x54 0x52 0x4f 0x4d 0x4c 0x4c    U.TROMLL
02F0   0x4e 0x4f 0x4f 0x4f 0x4d 0x4d 0x4e 0x50    NOOOMMNP
02F8   0x52 0x57 0x5c 0x5e 0x5e 0x5c 0x58 0x53    RW\^^\XS
0300   0x4e 0x4a 0x47 0x44 0x43 0x41 0x43 0x44    NJGDCACD
0308   0x41 0x3d 0x3b 0x38 0x38 0x39 0x39 0x39    A=;88999
0310   0x6f 0x0e 0x1b 0x09 0x4f 0x0e 0x38 0x36    o...O.86
0318   0x35 0x5b 0x0f 0x0e 0x1b 0x14 0x4f 0x0f    5[....O.
0320   0x35 0x36 0x36 0x38 0x3a 0x3c 0x3f 0x42    5668:<?B
0328   0x44 0x13 0x44 0x44 0x45 0x43 0x41 0x40    D.DDECA@
0330   0x3f 0x3f 0x3d 0x3b 0x3b 0x3a 0x39 0x37    ??=;;:97
0338   0x34 0x32 0x2f 0x2e 0x2c 0x2b 0x2a 0x29    42/.,+*)
0340   0x29 0x29 0x29 0x2b 0x2b 0x2b 0x28 0x26    )))+++(&
0348   0x26 0x28 0x2a 0x29 0x28 0x25 0x23 0x22    &(*)(%#"
0350   0x22 0x25 0x29 0x2d 0x30 0x34 0x36 0x39    "%)-0469
0358   0x3c 0x3d 0x3e 0x3f 0x3f 0x3f 0x3f 0x3f    <=>?????
0360   0x3e 0x3d 0x3d 0x3d 0x3f 0x3f 0x3f 0x40    >===???@
0368   0x40 0x42 0x44 0x44 0x45 0x47 0x13 0x47    @BDDEG.G
0370   0x46 0x47 0x47 0x47 0x46 0x46 0x45 0x44    FGGGFFED
0378   0x43 0x13 0x43 0x13 0x43 0x94 0x0e 0x1b    C.C.C...
0380   0x32 0x56 0x0e 0x43 0x43 0x42 0x47 0xbe    2V.CCBG.
0388   0x10 0x0e 0x1b 0x05 0x57 0x0f 0x46 0x45    ....W.FE
0390   0x45 0x44 0x44 0x44 0x44 0x44 0x43 0x43    EDDDDDCC
0398   0x42 0x42 0x41 0x40 0x3e 0x3d 0x3d 0x3c    BBA@>==<
03A0   0x3c 0x3d 0x3e 0x3f 0x3f 0x3f 0x3e 0x3e    <=>???>>
03A8   0x3e 0x3e 0x3f 0x3f 0x40 0x41 0x42 0x42    >>??@ABB
03B0   0x42 0x43 0x43 0x42 0x41 0x40 0x40 0x41    BCCBA@@A
03B8   0x42 0x42 0x42 0x41 0x41 0x40 0x40 0x40    BBBAA@@@
03C0   0x40 0x40 0x40 0x3f 0x41 0x42 0x43 0x43    @@@?ABCC
03C8   0x43 0x42 0x42 0x42 0x42 0x41 0x41 0x3f    CBBBBAA?
03D0   0x3e 0x3d 0x3c 0x3c 0x3d 0x3d 0x3d 0x3d    >=<<====
03D8   0x3c 0x3c 0x3b 0x3a 0x39 0x38 0x37 0x37    <<;:9877
03E0   0x36 0x37 0x38 0x38 0x37 0x37 0x37 0x35    67887775
03E8   0x35 0x36 0x36 0x13 0x36 0x13 0x36 0x34    566.6.64
03F0   0x33 0x32 0x32 0x32 0x32 0x32 0x32 0x31    32222221
03F8   0x32 0x0e 0x3c 0x32 0x47 0x08 0xb3 0x20    2.<2G.. 
```
#### decoded:
```python
'0000   0x40 0x40 0x41 0x13 0x42 0x13 0x46 0x4a    @@A.B.FJ\n0008   0x13 0x4c 0x13 0x4e 0x13 0x4f 0x13 0x50    .L.N.O.P\n0010   0x13 0x51 0x13 0x52 0x0e 0x5a 0x05 0x40    .Q.R.Z.@\n0018   0x08 0x13 0x53 0x54 0x13 0x55 0x13 0x55    ..ST.U.U\n0020   0x53 0x53 0x52 0x52 0x51 0x51 0x51 0x51    SSRRQQQQ\n0028   0x54 0x5e 0x65 0x6a 0x6c 0x6e 0x6e 0x6f    T^ejlnno\n0030   0x70 0x71 0x71 0x72 0x73 0x73 0x75 0x76    pqqrssuv\n0038   0x72 0x6e 0x6a 0x69 0x68 0x66 0x64 0x60    rnjihfd`\n0040   0x5e 0x5a 0x5d 0x67 0x6e 0x71 0x72 0x73    ^Z]gnqrs\n0048   0x73 0x74 0x74 0x73 0x74 0x74 0x74 0x74    sttstttt\n0050   0x73 0x73 0x73 0x71 0x6d 0x69 0x66 0x65    sssqmife\n0058   0x6b 0x70 0x72 0x71 0x70 0x70 0x6f 0x70    kprqppop\n0060   0x71 0x73 0x70 0x6c 0x68 0x65 0x63 0x62    qsplhecb\n0068   0x61 0x60 0x5f 0x61 0x63 0x69 0x6d 0x6c    a`_aciml\n0070   0x69 0x68 0x6c 0x13 0x72 0x74 0x74 0x76    ihl.rttv\n0078   0x77 0x76 0x76 0x7a 0x7e 0x0e 0x5a 0x05    wvvz~.Z.\n0080   0x48 0x08 0x0e 0x1a 0x0a 0x48 0x0b 0x0e    H....H..\n0088   0x3a 0x0a 0x48 0x0b 0x0e 0x3a 0x0b 0x48    :.H..:.H\n0090   0x0d 0x00 0x03 0xe7 0x0e 0x1a 0x0c 0x48    .......H\n0098   0x0e 0x13 0x02 0x0e 0x5a 0x0f 0x48 0x08    ....Z.H.\n00A0   0x0e 0x1a 0x14 0x48 0x0b 0x0e 0x3a 0x14    ...H..:.\n00A8   0x48 0x0b 0x0e 0x3a 0x14 0x48 0x0d 0x01    H..:.H..\n00B0   0x03 0xe6 0x0e 0x1a 0x17 0x48 0x0e 0xe7    .....H..\n00B8   0x0e 0x1a 0x19 0x48 0x0e 0x01 0x03 0x01    ...H....\n00C0   0x03 0x73 0xef 0x11 0x0e 0x1a 0x23 0x48    .s....#H\n00C8   0x0f 0xe2 0x0e 0x1a 0x25 0x48 0x0e 0x70    ....%H.p\n00D0   0x6c 0x6c 0x93 0x12 0x0e 0x1a 0x33 0x48    ll....3H\n00D8   0x0f 0x69 0x65 0x61 0x5c 0x59 0x59 0x59    .iea\\YYY\n00E0   0x57 0x51 0x4b 0x47 0x43 0x42 0x42 0x43    WQKGCBBC\n00E8   0x44 0x44 0x44 0x44 0x44 0x43 0x42 0x3f    DDDDDCB?\n00F0   0x40 0x42 0x44 0x45 0x45 0x46 0x47 0x48    @BDEEFGH\n00F8   0x4a 0x4c 0xa2 0x0e 0x1a 0x26 0x4b 0x0e    JL...&K.\n0100   0x4f 0x55 0x57 0xe5 0x11 0x0e 0x1a 0x32    OUW....2\n0108   0x4b 0x0f 0x5b 0x5c 0x5b 0x59 0x57 0x57    K.[\\[YWW\n0110   0x59 0x5c 0x5b 0x58 0x54 0x52 0x51 0x50    Y\\[XTRQP\n0118   0x4f 0x4f 0x50 0x50 0x51 0x52 0x53 0x56    OOPPQRSV\n0120   0x59 0x5a 0x5a 0x59 0x58 0x57 0x56 0x58    YZZYXWVX\n0128   0x59 0x5b 0x5e 0x61 0x64 0x66 0x68 0x69    Y[^adfhi\n0130   0x6b 0x6a 0x6a 0x6b 0x6d 0x6e 0x70 0x73    kjjkmnps\n0138   0x0e 0x1a 0x28 0x4f 0x08 0x75 0x77 0x79    ..(O.uwy\n0140   0x79 0x79 0x7a 0x7e 0x82 0x85 0x87 0x86    yyz~....\n0148   0x04 0x0e 0x3a 0x27 0x50 0x0e 0x04 0x0e    ..:\'P...\n0150   0x3a 0x28 0x50 0x0e 0x85 0x04 0x0e 0x3a    :(P....:\n0158   0x29 0x50 0x0e 0x04 0x0e 0x3a 0x2d 0x50    )P...:-P\n0160   0x0e 0x13 0x83 0x04 0x0e 0x3a 0x32 0x50    .....:2P\n0168   0x0e 0x83 0x04 0x0e 0x3a 0x33 0x50 0x0e    ....:3P.\n0170   0x04 0x0e 0x3a 0x35 0x50 0x0e 0x84 0x86    ..:5P...\n0178   0xfa 0x0e 0x1a 0x04 0x51 0x0e 0xfa 0x0e    ....Q...\n0180   0x1a 0x05 0x51 0x0e 0x87 0x88 0x81 0x07    ..Q.....\n0188   0x11 0x0e 0x1a 0x0f 0x51 0x0f 0x80 0x13    ....Q...\n0190   0x7f 0x13 0x7d 0x13 0x7a 0x13 0x78 0x13    ..}.z.x.\n0198   0x76 0x13 0x73 0x71 0x70 0x71 0x75 0x77    v.sqpquw\n01A0   0x0e 0x1a 0x0f 0x52 0x08 0x78 0x77 0x76    ...R.xwv\n01A8   0x74 0x72 0x70 0x07 0x0e 0x3a 0x30 0x52    trp..:0R\n01B0   0x0e 0x6c 0x65 0x6b 0x24 0x13 0x0e 0x1a    .lek$...\n01B8   0x00 0x53 0x0f 0x65 0x60 0x5a 0x55 0x51    .S.e`ZUQ\n01C0   0x4e 0x4b 0x49 0x48 0x47 0x48 0x47 0x46    NKIHGHGF\n01C8   0x46 0x47 0x49 0x4c 0x4e 0x4f 0x4f 0x50    FGILNOOP\n01D0   0x51 0x51 0x4f 0x4c 0x89 0x0e 0x1a 0x09    QQOL....\n01D8   0x55 0x0e 0x4a 0x47 0x44 0x25 0x13 0x0e    U.JGD%..\n01E0   0x1a 0x14 0x55 0x0f 0x41 0x3d 0x3a 0x37    ..U.A=:7\n01E8   0x36 0x36 0x37 0x38 0x38 0x38 0x39 0x39    66788899\n01F0   0x39 0x39 0x39 0x38 0x36 0x35 0x0e 0x1a    999865..\n01F8   0x32 0x56 0x08 0x0e 0x1a 0x32 0x56 0x08    2V...2V.\n0200   0x33 0x32 0x0e 0x1a 0x00 0x57 0x08 0x0e    32...W..\n0208   0x1a 0x00 0x57 0x08 0x31 0x0e 0x1a 0x05    ..W.1...\n0210   0x57 0x08 0x0e 0x1a 0x05 0x57 0x08 0x0e    W....W..\n0218   0x1a 0x05 0x57 0x08 0x0e 0x1a 0x05 0x57    ..W....W\n0220   0x08 0x31 0x30 0x30 0x2f 0x0e 0x1a 0x19    .100/...\n0228   0x57 0x08 0x2d 0x2b 0x2b 0x2d 0x32 0x39    W.-++-29\n0230   0x7d 0x0e 0x1a 0x39 0x57 0x0e 0x40 0x46    }..9W.@F\n0238   0x49 0x70 0x12 0x0e 0x1b 0x0b 0x40 0x0f    Ip....@.\n0240   0x49 0x48 0x48 0x47 0x44 0x42 0x40 0x40    IHHGDB@@\n0248   0x42 0x42 0x42 0x42 0x42 0x42 0x43 0x43    BBBBBBCC\n0250   0x43 0x43 0x43 0x42 0x41 0x41 0x40 0x40    CCCBAA@@\n0258   0x40 0x3f 0x3f 0x3f 0x3f 0x3e 0x3e 0x3e    @????>>>\n0260   0x3e 0x3e 0x3d 0x3d 0x3c 0x3c 0x3b 0x39    >>==<<;9\n0268   0x37 0x36 0x35 0x34 0x33 0x33 0x32 0x33    76543323\n0270   0x35 0x36 0x36 0x36 0x36 0x35 0x34 0x33    56666543\n0278   0x32 0x31 0x30 0x30 0x2f 0x2f 0x30 0x31    2100//01\n0280   0x31 0x32 0x32 0x32 0x33 0x33 0x34 0x34    12223344\n0288   0x34 0x34 0x34 0x35 0x33 0x30 0x2e 0x2d    444530.-\n0290   0x13 0x2c 0x2e 0x30 0x30 0x2f 0x30 0x31    .,.00/01\n0298   0x32 0x32 0x33 0x33 0x32 0x13 0x31 0x31    22332.11\n02A0   0x48 0x0e 0x1b 0x02 0x48 0x0e 0x33 0x34    H...H.34\n02A8   0x30 0x7e 0x10 0x0e 0x1b 0x10 0x48 0x0f    0~....H.\n02B0   0x33 0x38 0x3c 0x41 0x45 0x49 0x4d 0x50    38<AEIMP\n02B8   0x51 0x50 0x98 0x0e 0x1b 0x07 0x49 0x0e    QP....I.\n02C0   0x4f 0x50 0x4a 0x2c 0x0f 0x0e 0x1b 0x14    OPJ,....\n02C8   0x49 0x0f 0x4a 0x4b 0x4e 0x52 0x56 0x58    I.JKNRVX\n02D0   0x5b 0x5d 0x5d 0x5f 0x60 0x60 0x61 0x62    []]_``ab\n02D8   0x65 0x67 0x65 0x61 0x5e 0x5a 0x58 0x56    egea^ZXV\n02E0   0x55 0x54 0x53 0x54 0x55 0x53 0x52 0x53    UTSTUSRS\n02E8   0x55 0x13 0x54 0x52 0x4f 0x4d 0x4c 0x4c    U.TROMLL\n02F0   0x4e 0x4f 0x4f 0x4f 0x4d 0x4d 0x4e 0x50    NOOOMMNP\n02F8   0x52 0x57 0x5c 0x5e 0x5e 0x5c 0x58 0x53    RW\\^^\\XS\n0300   0x4e 0x4a 0x47 0x44 0x43 0x41 0x43 0x44    NJGDCACD\n0308   0x41 0x3d 0x3b 0x38 0x38 0x39 0x39 0x39    A=;88999\n0310   0x6f 0x0e 0x1b 0x09 0x4f 0x0e 0x38 0x36    o...O.86\n0318   0x35 0x5b 0x0f 0x0e 0x1b 0x14 0x4f 0x0f    5[....O.\n0320   0x35 0x36 0x36 0x38 0x3a 0x3c 0x3f 0x42    5668:<?B\n0328   0x44 0x13 0x44 0x44 0x45 0x43 0x41 0x40    D.DDECA@\n0330   0x3f 0x3f 0x3d 0x3b 0x3b 0x3a 0x39 0x37    ??=;;:97\n0338   0x34 0x32 0x2f 0x2e 0x2c 0x2b 0x2a 0x29    42/.,+*)\n0340   0x29 0x29 0x29 0x2b 0x2b 0x2b 0x28 0x26    )))+++(&\n0348   0x26 0x28 0x2a 0x29 0x28 0x25 0x23 0x22    &(*)(%#"\n0350   0x22 0x25 0x29 0x2d 0x30 0x34 0x36 0x39    "%)-0469\n0358   0x3c 0x3d 0x3e 0x3f 0x3f 0x3f 0x3f 0x3f    <=>?????\n0360   0x3e 0x3d 0x3d 0x3d 0x3f 0x3f 0x3f 0x40    >===???@\n0368   0x40 0x42 0x44 0x44 0x45 0x47 0x13 0x47    @BDDEG.G\n0370   0x46 0x47 0x47 0x47 0x46 0x46 0x45 0x44    FGGGFFED\n0378   0x43 0x13 0x43 0x13 0x43 0x94 0x0e 0x1b    C.C.C...\n0380   0x32 0x56 0x0e 0x43 0x43 0x42 0x47 0xbe    2V.CCBG.\n0388   0x10 0x0e 0x1b 0x05 0x57 0x0f 0x46 0x45    ....W.FE\n0390   0x45 0x44 0x44 0x44 0x44 0x44 0x43 0x43    EDDDDDCC\n0398   0x42 0x42 0x41 0x40 0x3e 0x3d 0x3d 0x3c    BBA@>==<\n03A0   0x3c 0x3d 0x3e 0x3f 0x3f 0x3f 0x3e 0x3e    <=>???>>\n03A8   0x3e 0x3e 0x3f 0x3f 0x40 0x41 0x42 0x42    >>??@ABB\n03B0   0x42 0x43 0x43 0x42 0x41 0x40 0x40 0x41    BCCBA@@A\n03B8   0x42 0x42 0x42 0x41 0x41 0x40 0x40 0x40    BBBAA@@@\n03C0   0x40 0x40 0x40 0x3f 0x41 0x42 0x43 0x43    @@@?ABCC\n03C8   0x43 0x42 0x42 0x42 0x42 0x41 0x41 0x3f    CBBBBAA?\n03D0   0x3e 0x3d 0x3c 0x3c 0x3d 0x3d 0x3d 0x3d    >=<<====\n03D8   0x3c 0x3c 0x3b 0x3a 0x39 0x38 0x37 0x37    <<;:9877\n03E0   0x36 0x37 0x38 0x38 0x37 0x37 0x37 0x35    67887775\n03E8   0x35 0x36 0x36 0x13 0x36 0x13 0x36 0x34    566.6.64\n03F0   0x33 0x32 0x32 0x32 0x32 0x32 0x32 0x31    32222221\n03F8   0x32 0x0e 0x3c 0x32 0x47 0x08 0xb3 0x20    2.<2G.. '
```
### end stats
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 20L,
           'packets.transmit': 21L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 49L,
         'packets.transmit': 49L}}
```
