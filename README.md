# Python Send-Receive
# import socket, sys
# s=socket.socket(socket.AF_INET, socket.SOCK_DGRAM)
# max=65535
# port=1060
# if sys.argv[1:]==['server']: 
#       s.bind(('127.0.0.1',port))
#       print s.getsockname(), 'dinleniyor'
#       while True:
#         data, address=s.recvfrom(max)	
#         print'Istemci',address,'uzerinden yaziyor..',repr(data)
#         s.sendto('Veri boyutu %d byte'%len(data),address)
# elif sys.argv[1:]==['client']:
#       s.sendto('Client mesaj yolladi',('127.0.0.1',port))
#       data, address=s.recvfrom(max)
#       print 'Server', address, 'uzerinden yaziyor', repr(data)
# else:
#       print>>sys.stderr,'kullanimi: Ornek.py server|client'



