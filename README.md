# GTA-SAN-Mods-THAI
Grand Theft Auto: San Andreas Mods text thai

#วิธีการติดตั้ง Mods
1.โหลดไฟล์ cleo (https://cleo.li/) แล้วติดตั้งให้เรียบร้อย
2.โหลดไฟล์ script Directfont จาก โฟลเดอร์ scripts บน repo นี้ได้เลย
- โหลด directFont.asi กับ directFont.ini
- เอาไปไว้ที่
~~~~
folder_game/scripts/
~~~~
3.โหลด ไฟล์ https://github.com/watchakorn-18k/GTA-SAN-Mods-THAI/blob/main/text/american.gxt 
- เอาไปไว้ที่
~~~~
folder_game/text/
~~~~


#แก้ไขข้อความ
1.โหลดโปรแกรม https://github.com/watchakorn-18k/GTA-SAN-Mods-THAI/blob/main/sagxtedit.rar
2.แตกไฟล์ออกให้เรียบร้อย
3.จากนั้นเปิด โฟลเดอร์ที่แตกไฟล์ออกมาแล้ว เปิดโปรแกรม sagxtedit
4.เมื่อเปิดเสร็จแล้วให้ไปที่ 
~~~~
เมนู File>Language>English
~~~~ 
เพื่อเซ็ทค่าเป็นภาษาอังกฤษก่อน
5.จากนั้นไปที่ 
~~~~
เมนู File>Open>folder_game/text/american.gxt
~~~~
6.แก้ไขข้อความได้เลย หลังจากแก้ไขข้อความเสร็จให้คลิกที่ ข้อความอะไรก็ได้ 1 ครั้ง แล้ว save ถ้าไม่คลิกโปรแกรมมันจะบันทึก 
#น่าจะประมาณนี้ส่วนใครแปลแล้วอยากให้อัพเดทก็ส่งไฟล์มาให้ผม โดย การ Fork ไปแล้ว ก็อัพไฟล์ลงมาได้เลยแล้วค่อย pull requests

#แก้ไข Font
สามารถแก้ได้ที่ ไฟล์ directFont.ini ที่
~~~~
folder_game/scripts/
~~~~
~~~~
FontName=      คือชื่อ font ที่ลงในเครื่องแล้วที่ผมไม่ใส่เพราะ font มันไม่สมบูรณ์เลยไม่ใส่ปรากฏว่ามันใช้ได้แต่ไม่สวย เหมือนเป็น font เริ่มต้นของ windows 10 ถ้าใครแก้ไขได้ก็บอกได้ครับผม
~~~~
~~~~
Height=70     ความสูงของข้อความ
Width=70      ความกว้างของข้อความ
~~~~
~~~~
ScaleFactor.x=0.4  สเกล x
ScaleFactor.y=0.5  สเกล y
~~~~
~~~~
Weight=200   ความหนา
Italic=0     ตัวเอียงถ้าต้องการให้เอียงก็เปลี่ยนเป็น 0
CharSet=1    ไม่รู้
OutputPrecision=0   อย่าปรับไม่งั้นเกมค้าง
Quality=0           น่าจะคุณภาพ
PitchAndFamily=0    ไม่รู้
UpcaseAlways=0      ปรับเป็น 0 เพราะ ถ้าเราปรับเป็น 1 ตัวอักษณอังกฤษจะเป็น พิมพ์ใหญ่ทั้งหมด แต่ข้อความไทยก็จะเพี้ยนตาม

ReplaceUnderscoreWithSpace=0 ไม่รู้
~~~~
