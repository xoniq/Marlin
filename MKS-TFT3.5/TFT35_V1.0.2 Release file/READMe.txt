1��������Ҫ���µ����ݰ����¶�Ӧ�ļ�������SD����

 (1)�����������ļ���mks_config.txt
 (2)������ͼƬ��    mks_pic
 (3)�������ֿ⣺    mks_font
 (4)������TFT�̼��� mkstft35.bin
 (5)������Wifi�̼���MksWifi.bin

2��ʹ��SD�����������ļ�ʱ����Ҫ�������ļ����޸�Ϊ��mks_config.txt

3�����Բο�Example�ļ����е����̡�

4��TFT70_V1.0.2�޸����ݣ�
��1�����޸�������桰�رյ��������������
��2�����޸������ӡ��ʱ��ת�����ݵ�����
��3����˫��ͷ��ӡ�С����١��󡰷��ء���ͷ��������
��4�������bootloader��ת����
��5�����޸Ķ��������ӡֹͣ����
��6�����޸�5��rend�ض��г�������

//////////////////////////////////////////////////////////////

1,According to the content that needs to be updated, copy the following file to the SD card:

 (1)��update the config file��mks_config.txt
 (2)��update images��         mks_pic
 (3)��update font��           mks_font
 (4)��update TFT firmware��   mkstft35.bin
 (5)��update Wifi firmware��  MksWifi.bin

2,When using the SD card to update the configuration file, you need to change the configuration file name to: mks_config.txt

3, You can refer to the Example folder's routines.

4, The firmware of V_1.0.2 modified content :
(1)��Fix the bug that "zero" interface "turn off the motor" does not work.
(2)��Fix the bug that network printing does not transfer data sometimes.
(3)��Fix the bug that extrusion is error after change print speed and return in the double nozzle printing.
(4)��Added the ablity to display rotation of bootloader.
(5)��Fix the bug that print stop due to card reading error.
(6)��Fix the bug that define line number error after 5 times resend.


