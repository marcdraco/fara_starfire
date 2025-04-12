# fara_starfire
A separate board featuring just a balanced line amplifier.

![image](https://github.com/user-attachments/assets/5837cacb-649c-49ef-ba9d-cafe50bbea5d)

As shown, Fara is configured with a bipolar supply fed by 2 x 2K2 resistors in the source and drain circuit. This should work quite well with the Happy capsule adaptor or the original head as designed and built by Matthew Perks for the Ulitmate USB-C microphone project.

With some small modifications (remove the 2K2 resistors and replace one with 680R and insert a 680R in the free pads configures the board (R4) for P12-P15 supply for use with capsule. Most users won't need this as adapters like Jaime are single supply balanced and intended for very long cable runs.

Fara does not have an internal power supply and requires +15 and -15 volt supplies. If you need a power supply the Liza Starfire board (based on the power supply from the Michelle 4.0 is suitable). Line regulation is not required (17V supplies, see Self's "Small Singal Design" should give slightly better performance - more gain). The circuit should operated from around +/-10V (with a reduction in maximum gain) and is quite sensitive to supply noise so that must be factored in. 

NOTE: as of this writing Fara has not undergone testing (it's next in line) so any builds must be considered experimental. It's based on a known good circuit but the board itself is untested. I will have some made up on the next batch.
