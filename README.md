# 4Eyes
  
    the 4eyes: Subdomain and domain scans. This program has the spider feature.
    the 4eyes: Subdomain ve Domain tarar. Bu program spider özelliğine sahiptir.
Required Modules / Gerekli Modüller

    requests
    argparse
    colorama
    urllib
    os  
    re
    random
    time
=====================================================================================================
   
   $ python3 main.py -h

            usage: main.py [-h] [-u URL] [-s SELECT] [-o OUTPUT]

            optional arguments:
              -h, --help  show this help message and exit
              -u URL      enter url: 'https://www.example.com'
              -s SELECT   method: [1]spider, [2]subdomain, [3]domain
              -o OUTPUT   output: noname.txt
  
=====================================================================================================

  $ python3 main.py -u https://www.example.com -s 1 -o output.txt
  
  
               ██╗  ██╗███████╗ ██████╗ ███████╗███████╗
               ██║  ██║██╔════╝██╔════╝ ██╔════╝██╔════╝
               ███████║█████╗  ██║  ███╗█████╗  ███████╗
               ╚════██║██╔══╝  ██║   ██║██╔══╝  ╚════██║
                    ██║███████╗╚██████╔╝███████╗███████║
                    ╚═╝╚══════╝ ╚═════╝ ╚══════╝╚══════╝


                        ******* SPIDER *******
                        
      ==============================
      |  [+] Found URL: https://www.example.com.tr/imghp?hl=tr&tab=wi
      ==============================
      ==============================
      |  [+] Found URL: https://www.example.com.tr/intl/tr/about/products?tab=wh
      ==============================
      ==============================
      |  [+] Found URL: https://www.example.com/preferences?hl=tr
      ==============================
      [+] Created output.txt
=====================================================================================================


