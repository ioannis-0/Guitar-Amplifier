### **Personal Project: Guitar Amplifier**
For this project, Ioannis and Daniel collaborated to design a guitar amplifier. Kicad was used to create a printed circuit board (PCB) compatible with an electric guitar to amplify its output volume.

This project is made up of two phases, with the first one being the **Creation of the PCB**  and the second being the **Testing** phase.

**Creation of the PCB:** Creation of the guitar amplifier PCB was done using KiCad. During this period, issues occured specifically concerning component selection. The components of an operational amplifier, power barrel connector, audio jack, and potentiometer were the main issues that arose. This issue was resolved through thorough research to identify components most compatible with our design goals: 

Operational amplifier = TL072 Lo/Noise 2XJFET Op. Amplifier (https://www.altronics.com.au/p/z2872-tl072-lo-noise-2xjfet-op-amplifier/?srsltid=AfmBOop0Bf4LZ-UD45hlEh1Mb5qex_sKeyiiGoEN5xp1L9ImB8eifREcn_Q)

Power barrel connector = DCJ200-10-A-K1-K (https://www.digikey.com/en/products/detail/gct/DCJ200-10-A-K1-K/9859579?utm_campaign=buynow&utm_medium=aggregator&utm_source=snapeda)

Audio jack = RJ3VM (https://www.mouser.com/ProductDetail/REAN/RJ3VM?utm_campaign=mouser&qs=0rbOLB9uh%252BCOWk8%2FAwcx4Q%3D%3D&utm_medium=online&utm_source=snapedaonline&utm_content=model)

Potentiometer = TC33X-2-103E (https://www.digikey.com/en/products/detail/bourns-inc/TC33X-2-103E/612858?utm_campaign=buynow&utm_medium=aggregator&utm_source=snapeda)

After using these components a DRC (Design Rule Checking) was ran, the results showing no errors.

<ins> This is the KiCad file for the PCB: </ins>          
https://github.com/ioannis-0/Guitar-Amplifier/tree/main/Final%20personal%20project

<ins> Image of the PCB on KiCad: </ins>  
<img src="bf1d6cce-1c7d-4efb-b69f-7e2322597bed.JPG" width="700" >

**Testing:** The PCB was tested on an electric guitar (Squier Sonic Stratocaster). The testing we conducted on this electric guitar was a success, as we were able to increase the volume output of the guitar using the PCB we had created. As no serious problems occurred during the testing phase.

<ins> Image of the testing of the PCB: </ins>  
https://www.youtube.com/watch?v=hHbWF1Bvgf4

<ins> Image of the physical PCB: </ins>  
<img src="Screenshot 2026-01-18 224805.png" width="700" >
