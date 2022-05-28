 Date: 08-05-2022 15:07
 
 **Referents**
 [[Digital circuit 3 Karnaugh map.pdf]]
 
----

### ທິດສະດີບູລິນ ເພື່ອຄັດຈ້ອນສົມຜົນໂລຊິກ
> 1.
  >![[bl1.png]]
> 2. 
>    ![[bl2.png]]
> 3. ![[bl3.png]]
> 4. ![[bl4.png]]

ເພື່ອຄວາມເຂົ້າໃຈ ແນະນຳໄປເບິ່ງວິດີໂອ

<iframe width="560" height="315" src="https://www.youtube.com/embed/RO5alU6PpSU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## K-map for 2 inputs(A, B)

>ເພື່ອເຂົ້າໃຈສະໄລ້ໜ້າ**2** ໃນບົດຮຽນທີ່ອາຈານໃຫ້
A = 0 is NOT A
A = 1 is A
B = 0 is NOT B
B = 1 is B


![[3.1.png]]


![[3.1.2.png]]
ສຳລັບຜົນອອກ ແມ່ນໃຊ້ເທັກນິກ**ການບວກ ຫຼືການ AND**
![[2v.png]]

### ການຄັດຈ້ອນ
#### ຕົວຢ່າງ 1.
ຄັດຈ້ອນສົມຜົນ $$AB+\overline A B = B(A + \overline A)=B$$
- ກ່ອນອື່ນຕ້ອງສ້າງຕາຕະລາງແບບນີ້
![[mtex1.1.png]]
- ຈາກນັ້ນຄິດໄລ ຫາກ A=1 ເຄິງໜຶ່ງ ແລະ =0 ເຄິ່ງໜຶ່ງມັນຈະຖືກຄັດອອກ(ໝົດໄປ)

![[mtex1.2.png]]
ຫຼືຈະອິງຕາມຕາຕະລາງຄ່າຄວາເປັນຈິງ ຫຼືອາໄສການບວກກໍໄດ້
- ຈາກນັ້ນຈະໄດ້
![[mtex1.3.png]]

- ຈາກນັ້ນເລືອກເອົາຫ້ອງທີ່ມີເລກ 1 ທີ່ລຽງເປັນແຖວຫຼືເປັນຖັນກໍໄດ້ ໂດຍຈຳນວນເລກ 1 ຈະຕ້ອງເປັນ 2^ (2,4,8,16,32... ໝາຍເຖິງຈຳນວນເລກ 1 ຕ້ອງເປັນກຳລັງຂອງ2) ເຊິ່ງໃນນີ້ເຮົາເລືອກເອົາແຖວທີ 2
![[mtex1.png]]
- ຄ່າທັງສອງແມ່ນແທົ່າກັບ B ນັ້ນໝາຍຄວາມວ່າ Yຄັດຈ້ອນ=B
