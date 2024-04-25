Το project δημιουργήθηκε με το πρόγραμμα CubeMX μέσω του STM32CubeIDE. Για χρήη αρκεί να γίνει import στο CubeIDE.

Οι δικές μας τροποποιήσεις είναι ό,τι βρίσκεται εντός των // USER CODE segments.
Τροποποιήθηκαν τα αρχειά Core/Src/main.c, Core/Inc/app\_conf.h, STM32\_WPAN/App/app\_zigbee.c, STM32\_WPAN/App/app\_zigbee.h .

Σημειώνεται ότι ο αισθητήρας θερμοκρασίας αναμένεται να συνδεθεί στο A0 pin. Οι μετατροπές τιμών θερμοκρασίας έγιναν με βάση τα specifications του αισθητήρα LM35 που χρησιμοποιήθηκε, δηλαδή Vadc = 10mv/(degrees C)
