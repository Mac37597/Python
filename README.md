import socket import
threading
HOST = '127.0.0.11
def receive messages (client_socket):
while True:
ary.
message = client_ socket.recv(1024).decode('utf-8')
if message:
print (message)
except:
client_socket.close()
break
O Search
2E8E
def main():
client_socket = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
client_socket.connect ((HOST, PORT))
print(f"Connect au serveur (HOST): (PORT}")
thread - threading. Thread (target-receive messages, args=(client_socket,)) thread.start)
whale rue.
message = input()
client_socket send (message.encode('utf-8'))
_name_ == "_main_":
