## Day 0
 <summary> Summary <Yosys></Yosys>
	
I installed the needed tools.

</details>	
	
 <details>
 <summary> Yosys </summary>


 I installed Yosys using the following commands:
 ```bash
git clone https://github.com/YosysHQ/yosys.git
cd yosys-master 
sudo apt install make 
sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
  make 
  sudo make install
 ```

Screenshot of Yosys installation:
![yosys-install](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/6dea691a-e93e-4900-b155-73eecda11ef3)

Yosys is installed!

![Screenshot from 2023-08-02 10-45-41](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/b53051af-8c34-40ee-b18f-bf72361ad167)
</details>

<details>
<summary> iverilog </summary>

I installed iverilog using the commands below:

sudo apt-get install iverilog

![Screenshot from 2023-08-02 10-48-04](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/3b9e8854-2066-494e-a360-7ea0131b8249)

</details>

<details>
<summary> gtkwave </summary>

I installed gtkwave using the commands below:

sudo apt update
sudo apt install gtkwave

Below are the screenshots showing steps for installing gtkwave:
![Screenshot from 2023-08-02 10-49-08](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/94c45106-3810-4b90-bf06-9990a4d761aa)

![Screenshot from 2023-08-02 10-50-19](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/55bf15af-c60a-495e-8848-8eb3419359c7)

Gtkwave window:
![Screenshot from 2023-08-02 11-02-07](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/518bcda6-6892-4596-801b-9ce4dfe64ba4)

</details>

<details>
<summary> OpenSTA </summary>

I installed OpenSTA using the commands below:

sudo apt-get install cmake clang gcctcl swig bison flex

git clone https://github.com/The-OpenROAD-Project/OpenSTA.git

cd OpenSTA

mkdir build

cd build

cmake ..

make

![Screenshot from 2023-08-06 21-20-47](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/a6983317-5fcd-4097-bfcb-4ab47a71d3f3)

![Screenshot from 2023-08-06 21-22-31](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/e43702fe-1bc3-4c59-93d3-f9a71b607bb9)

![Screenshot from 2023-08-06 21-26-33](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/280631fe-c686-4383-8a27-30de4624992f)



</details>

<details>
<summary> ngspice </summary>

I installed ngspice using the commands below:

After downloading the tarball from https://sourceforge.net/projects/ngspice/files/ to a local directory, unpack it using:

$ tar -zxvf ngspice-40.tar.gz

$ cd ngspice-40

$ mkdir release

$ cd release

$ ../configure  --with-x --with-readline=yes --disable-debug

$ make

$ sudo make install

![Ngpice1](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/0536c5c4-9b74-4c37-9a06-cf2478e1cc5d)

![Ngpice-Release](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/cd3f4751-0288-44e2-9da6-1f3677da1cd3)

![Make-Ngpice](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/60a9258d-ac40-434f-92f2-61a7d62ca0d1)

![Make - Ngpice2](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/12b888e0-c75e-4156-8039-58257d9310f2)


</details>

<details>
<summary> magic </summary>

I installed magic using the commands below:

$ sudo apt-get install m4

$ sudo apt-get install tcsh

$ sudo apt-get install csh

$ sudo apt-get install libx11-dev

$ sudo apt-get install tcl-dev tk-dev

$ sudo apt-get install libcairo2-dev

$ sudo apt-get install mesa-common-dev libglu1-mesa-dev

$ sudo apt-get install libncurses-dev

git clone https://github.com/RTimothyEdwards/magic

cd magic

./configure

make

make install


![Magic-1](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/82206280-c213-45fd-97f4-469bab0ebfeb)

![Magic-4](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/0d254ad6-6d90-4887-bc0a-c758eee429ef)

![Magic-5](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/745b8d1c-7036-443c-9b0d-5c0ae2dbd949)


</details>
<details>
	
<summary> OpenLANE </summary>

I installed OpenLANE using the commands below:

sudo apt-get update

sudo apt-get upgrade

sudo apt install -y build-essential python3 python3-venv python3-pip make git

sudo apt install apt-transport-https ca-certificates curl software-properties-common

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

echo "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt update

sudo apt install docker-ce docker-ce-cli containerd.io

sudo docker run hello-world

sudo groupadd docker

sudo usermod -aG docker $USER

sudo reboot

![OpenLane-1](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/f3c3c4f0-1d11-4134-a75f-f21ae4da3d37)

![OpenLane-2](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/114def87-4c34-4b8b-a29c-de4b470a9172)

# After reboot

docker run hello-world

![Docker1](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/95ef3694-502d-41f4-b5b5-f770dfe62e4f)

</details>

<details>

<summary> Check Dependency </summary>

git --version

docker --version

python3 --version

python3 -m pip --version

make --version

python3 -m venv -h

![Checking Dependency](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/099ad7c9-ec8f-4a7e-a318-2f6c4f5333e2)

</details>

<details>

<summary> PDKs and Tools </summary>


I installed PDK using the following commands:

cd $HOME 

git clone https://github.com/The-OpenROAD-Project/OpenLane

cd OpenLane

make

make test


![PDKinstalled](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/2ae34fc4-95de-48c7-976b-21d051318685)

![PDK2](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/ccc798ea-9c47-4465-b7a3-deb0942a7c40)

</details>

## Day 1

<details>
 <summary> Summary </summary>

This section shows how I simulated and synthesized a 2x1 mux using iverilog and yosys respectively. iverilog generates from the RTL design and its testbench a value changing dump file (vcd). gtkwave is the tool used to plot the simulation results of the design. Yosys is a tool which synthesizes RTL designs into a netlist. It is also used to test the synthesized netlist when we provide it with a testbench.

</details>	
	
<details>
 <summary> Verilog codes </summary>
The verilog codes of the 2x1 mux (good_mux.v) and its testbench (tb_good_mux.v) are taken from https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git

</details>

 <details>
 <summary> Simulation: iverilog and gtkwave </summary>
 
 I used the following commands to simulate and view the plots of the RTL design:
 
 ```bash
 iverilog good_mux.v tb_good_mux.v
 ./a.out
 gtkwave tb_good_mux.vcd
 ```
	
 Below is the screenshot of the gtkwave plots:
 
![Screenshot from 2023-08-11 22-53-00](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/f9bf9399-c319-46c7-b58f-29e97f2a978d)

The verilog code good_mux.v and its testbench tb_good_mux.v:

![Screenshot from 2023-08-11 22-57-52](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/ad883da9-fafe-40e5-96d5-004e5fb73625)


 
 </details>

<details>
 <summary> Synthesis: Yosys </summary>
	
 In the directory of the verilog files, I used the following commands to synthesize and view the synthesized deisgn:
 
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog good_mux.v
yosys> synth -top good_mux
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
 ```
 Below is the screenshot of the synthesized design:
 
![Screenshot from 2023-08-11 23-15-00](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/a9121038-85d7-4db0-94c9-b194b76a1442)


	
 I used the following commands to generate the netlist:
 
 ```bash
 yosys> write_verilog <good_mux_netlist.v>
 yosys> write_verilog -noattr <good_mux_netlist.v>
 ```
 
 Below is the screenshot of the generated netlist:
 
 ![Screenshot from 2023-08-11 23-19-26](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/738dc136-96f1-4c36-85e3-3b7dfe6dc585)

 
 </details>
