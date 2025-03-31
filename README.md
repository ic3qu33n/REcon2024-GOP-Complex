# REcon2024-GOP-Complex
## GOP Complex: Image parsing bugs, EBC polymorphic engines and the Deus ex machina of UEFI exploit dev
          
This repo contains the slidedeck and PoCs presented at REcon 2024 for my talk "GOP Complex: Image parsing bugs, EBC polymorphic engines and the Deus ex machina of UEFI exploit dev"


 
## REcon2024 slidedeck          
### REcon2024 talk slidededeck is in the [REcon2024-slides-GOP-Complex](REcon2024-slides-GOP-Complex/) folder.            
 

## REcon2024 POC
## PoC will be made publicly available at some point in the future.  
The link for the POC will be added here when I make it public.

---         
# Talk description:
BIOS Hacking is back and it’s badder than ever.
Legacy BIOS is old news and UEFI is the new reigning queen bee of Platform Firmware implementations. This changing of the guard brings new challenges and mitigations for bootkit writers to thwart and bypass, as well as the opportunity for creative exploits and groundbreaking techniques in UEFI exploit development.  

This talk is a deep-dive on UEFI reverse engineering and exploit development, with a focus on new and creative UEFI exploit dev techniques. It will also cover strategies for finding new exploit targets within UEFI. Applicable both to seasoned veterans of UEFI/BIOS exploit dev, and those looking to break into the space, I’ll cover both UEFI RE and exploit dev essentials and new techniques to take your UEFI PoCs to the next level. This talk combines hardware hacking and platform firmware reverse engineering and exploit development and will cover the following: 

- UEFI software testing/debugging techniques with emulators
- UEFI hardware debugging and testing techniques
- UEFI reverse engineering 
- Assembly programming techniques for developing UEFI shellcode on different architectures (x86-64, aarch64 and EBC)
- PCI Option ROM hacking

What happens when you combine the exploit primitives in a vulnerable image parsing driver impacted by LogoFAIL, PCI Option ROM hacking, the oft-forgotten and neglected EBC (EFI Byte code) architecture and a dash of low-level graphics programming?
GOP Complex.


---

Hit me up with questions or feedback.

xoxo
ic3qu33n
