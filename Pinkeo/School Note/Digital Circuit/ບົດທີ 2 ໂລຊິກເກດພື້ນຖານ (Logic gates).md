#### ບົດທີ 2 ໂລຊິກເກດພື້ນຖານ (Logic gates)

##### Referents:
- file: [[Digital Circuit/Materials/digital circuit unit 2 logic gate.pdf]]

___

### Attributed of Logic Gate

  ໂລຊິກເກດພື້ນຖານມີ 3 ຊະນິດຄື: NOT gate, OR gate, AND gate ນອກນັ້ນຍັງມີເກດພິເສດອີກຄື: NAND gate, NOR gate, Exclusive-OR gate(XOR), Exclusive-NOR gate(XNOR).
## **NOT gate**
ມີອິນພຸດດຽວ ແລະ ເອົ້າພຸດດຽວ
###### ສົມຜົນ: 
> $$ Y = \overline{A} $$

###### Truth table
 | INPUT A| OUTPUT Y|
 | ----- | ------ |
 | 0     | 1      |
 | 1     | 0      |

> ==ເປັນການປະຕິເສດ ຫາກອິນພຸດເປັນ 0 ເອົ້າພຸດຕ້ອງເປັນ 1==



###### Symbol
![[NOT gate Symbol]]

###### IC 
ນຳໃຊ້ໄອຊີ ເບີ **7404**
![[7404six-inverter.jpg]]

## **OR gate**
has two input up but got only one input
###### ສົມຜົນ
> $$ Y= A+B$$

read A or B not A plus B
> ==ໃຊ້ເຕັກນິກການບວກໃນການກາເອົ້າພຸດ==
###### Truth Table
| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 0   |
| 0   | 1   | 1   |
| 1   | 0   | 1   |
| 1   | 1   | 1    |

###### Symbol
![[OR gate Symbol]]
###### IC
use ic No. **7432**
![[74LS32-Pinout.gif]]


## **AND gate**
Has two input up and got only one output
###### ສົມຜົນ
> $$ Y = A.B$$

Read Y equal A and B, not A time B

> ==ໃຊ້ວິທີການຄູນເພື່ອຫາຄ່າເອົ້າພຸດ==

###### Truth Table
| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 0   |
| 0   | 1   | 0   |
| 1   | 0   | 0   |
| 1   | 1   | 1    |

###### Symbol
![[AND gate Symbol]]

###### IC
Use IC No.**7408**
![[7408-and-gate-pinout.png]]


## **NOR gate**
ສອງອິນພຸດຂຶ້ນໄປ ມີເອົ້າພຸດດຽວ
###### ສົມຜົນ
> $$Y=\overline{A+B}$$

ອ່ານວ່າ Y = A Nor B
> ==ເອົາອິນພຸດບວກກັນ ແລ້ວປະຕິເສດ==

###### Truth Table
| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 1   |
| 0   | 1   | 0   |
| 1   | 0   | 0   |
| 1   | 1   | 0    |

###### Symbol
![[NOR gate Symbol]]

###### IC
ໃຊ້ໄອຊີເບີ 7402
![[1454914384.gif]]

## **NAND gate**
###### ສົມຜົນ
> $$Y=\overline{A.B}$$

ອ່ານວ່າ Y = A nand B
>==ເປັນການເອົາອິນພຸດຄູນກັນ ແລ້ວປະຕິເສດ==

###### Truth Table
| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 1   |
| 0   | 1   | 1   |
| 1   | 0   | 1   |
| 1   | 1   | 0    |

###### Symbol
![[NAND gate Symbol]]

###### IC
ໃຊ້ໄອຊີເບີ **7400**
![[7400-Quad-2-input-NAND-gate-1.jpg]]

## **XOR gate**
###### ສົມຜົນ
> $$Y=\overline{A}B+A\overline{B}$$

> ==ອິນພຸດຄືກັນອອກ 0 ຕ່າງກັນອອກ 1 ຫາກມີຫຼາຍກວ່າ2ອິນພຸດແມ່ນໃຫ້ນັບເລກ1 ຫາກຈຳນວນຂອງເລກ1ເປັນຄີກອອກ 1 ຫາກເປັນຄູ່ອອກ 0 ==

###### Truth Table
| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 0   |
| 0   | 1   | 1   |
| 1   | 0   | 1   |
| 1   | 1   | 0    |

###### Symbol 
![[EXOR gate Symbol]]

###### IC
ໃຊ້ໄອຊີເບີ **7486**
![[7486_Quad_2-input_ExOR_Gates.png]]


## **XNOR gate**
###### ສົມຜົນ
> $$Y=AB+\overline{A} \overline{B}$$

> ==ຫາກອິນພຸດທັງສອງຄືກັນອອກ1 ຕ່າງກັນອອກ0 ຫາກມີອິນພຸດຫຼາຍກວ່າ2ຕົວໃຫ້ນັບຈຳນວນເລກ1ຫາກເປັນຈຳນວນຄີກອອກ0 ເປັນຄູ່ອອກ1==

###### Truth table
| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 1   |
| 1   | 0   | 0   |
| 0   | 1   | 0   |
| 1   | 1   | 1    |

###### Symbol 
![[EXNOR gate Symbol]]

###### IC
ນຳໃຊ້ໄອຊີເບີ **7466 or 74266** 
![[standard-package-of-xnor-gate.png]]

# ການປະຍຸກໃຊ້ universal gate
