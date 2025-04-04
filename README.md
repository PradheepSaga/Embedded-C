# Embedded-C
Essential C components used in Embedded Programming
Code	                        Result                         CPU usage
while(1) { printf(...); }	    Prints forever                 HIGH
while(1);	                    Infinite loop, no output       HIGH (hangs the CPU)
while(0) { printf(...); }     	Skipped                        NO
while(0);	                    Skipped (does nothing)         NO

While:-
⚙️ Real-World Embedded Use

    while(1) is used in embedded systems to keep the microcontroller alive (main loop).

    while(0); is rarely used in actual code, except for skipping blocks (like disabling a chunk during testing).
    
