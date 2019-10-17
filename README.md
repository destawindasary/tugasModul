def main() :
p =int(raw_input("Masukkan Panjang Balok\t: "))
l = int(raw_input("Masukkan Lebar Balok\t: "))
t = int(raw_input("Masukkan Tinggi Balok\t: "))

v = p*l*t
LP = 2*(p*l*p*t+l*t)

print"Volumr Balok = ",LP
os.system("pause")

if __name__ == "__main__":
	main()

