It's my begining with the zkSNARK.

File exercise is my solutions of the exercises from this website
https://hackmd.io/@gubsheep/S1Hz96Yqo

File GroupSignatures contains templates which can be use to send msg without revealing who send it. We just know the msg was send by someone from a gruop of people with public keys added as an input signal. RevealableGroupSig gives our option to show that we send msg using UnrevealRevealableGroupSig template. That is possible, because we use additional output signal from RevealableGroupSig, that we try reconstruct with our own sekret key. In UnrevealableGroupSig we don't have option to show that we send msg, but also there is no option to show that we didn't sent it, if our public key was use as an input signal. The last two templates create situation where our group have trusted admin. And admin is able to find who send msg.  


