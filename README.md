# HyperledgerTraining

Device Used: PC

Device Specifications: 4 GB RAM
                       Windows 8.1 Pro Operating System (64-bit)
                       Intel Core i3

Tools used: Virtualbox
            (inside virtual box) VS Code(for code editing purposes) Postman(application to see if the program is running)

Steps for applying the system:

Clone the repository given in the link

Replace the files (or backup before replacing for the purpose of having copy) on your fabric-samples/chaincode/fabcar/go and fabric-samples/fabcar directories with the ones inside this repository.

Open a terminal

Open the fabric-samples/fabcar in Terminal.

Type and press Enter: ./openScm.sh

Type and press Enter: node enrollAdmin.sh

(Optional) Type and press Enter: node registerUser.sh

(Optional) Type and press Enter: node rSupplier1.sh

(Optional) Type and press Enter: node rOEM.sh

Run the program

How to test the program:

To test all functions, type and press Enter: node app_scm.sh

is 3000.

(Optional) To test as supplier1, open a new Terminal window, type: node appSupplier1.sh

is 3001 and enter it.

NOTE: supplier1 can only raise an invoice (number 3 below).

(Optional) To test as OEM, open a new Terminal window, type and press Enter: node appOEM.sh

is 3002.

NOTE: OEM can only set that goods are received (number 4 below).
