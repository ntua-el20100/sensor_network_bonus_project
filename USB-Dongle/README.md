Ο κώδικας που χρησιμοποιήθηκε βασίζεται στα ενδεικτικά προγράμματα που παρέχονται στο CubeMX MCU package:  https://www.st.com/en/embedded-software/stm32cubewb.html

Για να χρησιμοποιηθεί το project θα πρέπει να τοποθετηθεί στο path: STM32Cube\_FW\_WB\_V1.19.0\_DongleClient/Projects/P-NUCLEO-WB55.USBDongle/Applications/Zigbee, επειδή εξαρτάται από αρχεία που βρίσκονται πιο ψηλά στο path.
Έπειτα στο IDE, File->Open Projects from File System... επιλέγεται ο φάκελος STM32CubeIDE εντός του project.

Τροποποιήθηκαν τα αρχειά Core/Src/main.c, Core/Inc/app\_conf.h, STM32\_WPAN/App/app\_zigbee.c, STM32\_WPAN/App/app\_zigbee.h .

Αφού γίνει compilation του προγράμματος και παραχθεί εκτελέσιμο από το IDE, θα πρέπει να χρησιμοποιηθεί το πρόγραμμα STM32CubeProgrammer, με το dongle σε DFU mode.
