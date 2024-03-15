# Socket-needed-extension-calculation
You have recently moved to a new house and realized there is only one socket available! Given your passion for conducting electricity experiments, you need at least B sockets in your new place. Fortunately, you have plenty of extension cords, and each extension has A sockets, utilizing one socket. 

import math

A, B = map(int, input().split())
extension_cords_needed = math.ceil((B - 1) / (A - 1))
print(extension_cords_needed)
