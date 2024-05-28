# Miners support Tuske

SRBMiner-MULTI https://github.com/doktor83/SRBMiner-Multi/releases/tag/2.5.3

XMRigCC https://github.com/Bendr0id/xmrigCC/releases/tag/3.4.1


## Solo Mining

Make sure your local Tuske Daemon is running and synchronization is complete.

xmrigDaemon.exe -o 127.0.0.1:20241 -a rx/tuske -u "Tuske Mainnet Address" --daemon

(Replace "Tuske Mainnet Address" with your own address)

## Pool Mining

xmrigDaemon.exe -o mine.tuske.network:3333 -a rx/tuske -u "Tuske Mainnet Address" -p x -k

(Replace "Tuske Mainnet Address" with your own address)

If you want to set the number of threads yourself, you can use the -t parameter
For example 
-t 10 
means using 10 threads

You can find pools that support TUSKE here:
https://miningpoolstats.stream/tuske
