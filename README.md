# c-program
c programs to program NI-6535 B card for time sequence of cold atom experiement

Compiling command:
gcc file_name.c -o execuatable_name -L"C:\Program Files (x86)\National Instruments\Shared\ExternalCompilerSupport\C\lib32\msvc" -lNIDAQmx

list of programs:
1. buffer card checking dynamic program: continuosly sends 1 and 0 signal at specified frequency
2. buffer card stati low signal to reset the buffer card
3. buffer card static high signal to check buffer card bu ouput
4. send_signal.c : to extracts the signal text file generated from the python file and send to the NI-card
5. checking digital card
6. checking analog card
7.  
