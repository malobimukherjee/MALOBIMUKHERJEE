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

## Day 2

<details>
 <summary> Summary </summary>

I first synthesized a multiple module (made of two submodules) at the multiple module level (both in hierarchical and flattened forms) then at the submodule level. Synthesis at the submodule level is important for two reasons: 1-) when we have multiple instances of same module (we synthesize once and replicate this netlist multiple times and stitch together the replicas to get the multiple module netlist, and 2-) when we want to divide and conquer (in massive designs) so that the tool can generate a portion by portion of the overall netlist and then we can stitch together the netlist portions to get the multiple module netlist.
After that, I sumulated the different flop designs using iverilog and gtkwave, then synthesized the designs.
Finally, I synthesized 2 designs that were special; their synthesis used optimizations.

</details>	
	
<details>
 <summary> Verilog codes </summary>
The verilog codes of the multiple module (multiple_modules.v), the D-flipflop with asynchronous reset (dff_asyncres.v), the D-flipflop with asynchronous set (dff_async_set.v), the D-flipflop with synchronous reset (dff_syncres.v), their respective testbenches (tb_*), mult_2.v and mult_8.v are taken from https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git

</details>
	
<details>
 <summary> Synthesis: multiple_modules level </summary>
		
I used the following commands to synthesize and view the design of the hierarchical multiple module:
		
```bash		
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog multiple_modules.v
yosys> synth -top multiple_modules
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show multiple_modules
yosys> write_verilog -noattr multiple_modules_hier.v
```
Below is the screenshot of the generated hierarchical design:
		
![Screenshot from 2023-08-11 23-58-21](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/709686b4-8fb6-4d46-8410-d6e7647bfff0)

	
Below is the screenshot of the generated hierarchical netlist:
		
![Screenshot from 2023-08-11 23-41-51](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/20ba868a-c681-4d19-8696-ee4a6fd133a8)


I used the following additional commands to synthesize and view the design of the flattened multiple module:
		
```bash
yosys> flatten
yosys> write_verilog -noattr multiple_modules_flat.v
```	
Below is the screenshot of the generated flattened design:
		
![Screenshot from 2023-08-11 23-58-50](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/4f6e70d7-989d-4efe-93fc-462d3cf0e3ca)


Below is the screenshot of the generated flattened netlist:
		
![Screenshot from 2023-08-12 00-00-40](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/b2f65aa7-eaa0-476b-b440-68cb30d415d7)

</details>
<details>
 <summary> Synthesis: sub_module1 level </summary>
		
I used the following commands to view the synthesized design of the submodule:
		
```bash		
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog multiple_modules.v
yosys> synth -top sub_module1
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show sub_module1
```
	
Below is the screenshot of the generated design:
		
![Screenshot from 2023-08-12 00-09-08](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/3b65c5cc-f4ec-464f-a0a0-3224b95eeb4b)


</details>
<details>
<summary> Simulation: dff with asynchronous reset </summary>

I used the following commands to simulate the RTL design of the dff with asynchronous reset:
	
```bash	
iverilog dff_asyncres.v tb_dff_asyncres.v
./a.out
gtkwave tb_dff_asyncres.vcd
```	
	
Below is the screenshot of the simulation:
	
![Screenshot from 2023-08-12 00-18-44](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/0a0f0992-3f6c-4c57-b6da-a36e8b017121)


</details>
<details>
<summary> Simulation: dff with asynchronous set </summary>
I used the following commands to simulate the RTL design of the dff with asynchronous set:
	
```bash	
iverilog dff_async_set.v tb_dff_async_set.v
./a.out
gtkwave tb_dff_async_set.vcd
```
	
Below is the screenshot of the simulation:

![Screenshot from 2023-08-12 00-22-20](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/33221b35-921e-4cb7-9dae-b86a91aa7c43)


</details>
<details>
<summary> Simulation: dff with synchronous reset </summary>
	
I used the following commands to simulate the RTL design of the dff with synchronous reset:
	
```bash	
iverilog dff_syncres.v tb_dff_syncres.v
./a.out
gtkwave tb_dff_syncres.vcd
```	
	
Below is the screenshot of the simulation:
	
![Screenshot from 2023-08-12 00-26-53](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/256f6704-3903-4ce3-8775-4c2033294c01)

</details>
<details>
 <summary> Synthesis: dff with asynchronous reset </summary>

I used the following commands to synthesize the design:
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_asyncres.v
yosys> synth -top dff_asyncres
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show dff_asyncres
```
Below is the screenshot of the synthesized design:
	
![Screenshot from 2023-08-12 00-36-00](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/35d0c3e9-5cb6-428f-a4a3-e8f1750935cf)

	
</details>
<details>
 <summary> Synthesis: dff with asynchronous set </summary>

I used the following commands to synthesize the design:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_async_set.v
yosys> synth -top dff_async_set
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show dff_async_set
```
Below is the screenshot of the synthesized design:

 
![Screenshot from 2023-08-12 00-40-59](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/ef617faf-6641-4aa9-ae9e-a5e9e9dfda8e)


</details>
<details>
 <summary> Synthesis: dff with synchronous reset </summary>
	
I used the following commands to synthesize the design:
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_syncres.v
yosys> synth -top dff_syncres
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show dff_syncres
```
Below is the screenshot of the synthesized design:

![Screenshot from 2023-08-12 00-46-08](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/d455a77c-df18-47a2-a992-b5128863a108)


</details>
<details>
 <summary> Synthesis: mult_2.v </summary>
	
I used the following commands to synthesize and view the design:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog mul_2.v
yosys> synth -top mul2
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show mul2
yosys> write_verilog -noattr mul2_net.v
```
	
Below is the screenshot of the synthesized design, note that no hardware was used (no cells are synthesised) as multiplying a 3-bit input by a power of two is equivalent to shifting for output:

![Screenshot from 2023-08-12 00-49-34](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/77236f16-b2df-40ab-9f9b-71e1ef0a4e0b)

	
Below is the screenshot of the netlist:
	
![Screenshot from 2023-08-12 00-51-21](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/6ddcaa91-2c45-47a8-a986-73bb0707630b)

	

</details>
<details>
 <summary> Synthesis: mult_8.v </summary>
	
I used the following commands to synthesize and view the design:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog mult_8.v
yosys> synth -top mult8
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show mult8
yosys> write_verilog -noattr mult8_net.v
```
	
Below is the screenshot of the synthesized design, note that no hardware was used (no cells are synthesised) as multiplying a 3-bit input (special case) by a nine is equivalent to replicating the input twice for output:
	
![Screenshot from 2023-08-12 00-54-54](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/8dfccf76-e3fa-4683-8a41-727e899d90e6)


Below is the screenshot of the netlist:
	
![Screenshot from 2023-08-12 00-55-56](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/46fd7dc6-c5c2-4512-97e9-43ebd930dcd7)



</details>

## Day 3
	
<details>
 <summary> Summary </summary>

I have synthesized designs with optimizations. Combinational logic optimizations include 1-) constant propagation (when the combination is just propagating a constant) and 2-) boolean logic optimization (when boolean rules are used to simplify the expression). Sequential logic optimizations include 1-) sequential constant propagation (when constant is propagated with clock involved), 2-) state optimization (when unused states are optimized), 3-) retiming (when logic is split to decrease timing of the different logic portions and increase frequency), and 4-) sequential logic cloning (when physical aware synthesis is done to optimize the floop plan)

</details>	
	
<details>
 <summary> Verilog codes </summary>

The verilog codes used (opt_*, dff_const*, tb_dff_const*, and counter_opt*) are taken from https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git

</details>
	
<details>
 <summary> Combinational logic optimizations: opt_check.v </summary>
I used the below commands to view the synthesized design of opt_check.v with optimizations:

	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog opt_check.v
yosys> synth -top opt_check
yosys> opt_clean -purge
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained optimized design, as we can see a 2-input and gate is realized as was expected when optimizations are applied:
	
![Screenshot from 2023-08-12 09-04-39](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/ef92c932-a2b0-4e54-903b-0b1febec76ff)


</details>
	

<details>
 <summary> Combinational logic optimizations: opt_check2.v </summary>
	I used the below commands to view the synthesized design of opt_check2.v with optimizations:
 ```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog opt_check2.v
yosys> synth -top opt_check2
yosys> opt_clean -purge
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
Below is the screenshot of the obtained optimized design, as we can see a 2-input or gate is realized as was expected when optimizations are applied:
	
![Screenshot from 2023-08-12 09-07-36](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/74368ea7-7d6e-4279-88fa-e4322d3cc823)



</details>
	
<details>
 <summary> Combinational logic optimizations: opt_check3.v </summary>
	
I used the below commands to view the synthesized design of opt_check3.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog opt_check3.v
yosys> synth -top opt_check3
yosys> opt_clean -purge
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained optimized design, as we can see a 3-input and gate is realized as was expected when optimizations are applied:
	
![Screenshot from 2023-08-12 09-11-03](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/f60f43f8-fbbf-494b-b967-921d78940fcf)

</details>
	
<details>
 <summary> Combinational logic optimizations: opt_check4.v </summary>
	
I used the below commands to view the synthesized design of opt_check4.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog opt_check4.v
yosys> synth -top opt_check4
yosys> opt_clean -purge
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained optimized design, as we can see a 2-input xnor gate is realized as was expected when optimizations are applied:
	
![Screenshot from 2023-08-12 09-14-08](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/29092c3a-a6cb-42a5-bb20-fcdc4d5898c4)

</details>

		
<details>
 <summary> Combinational logic optimizations: multiple_module_opt.v </summary>
	
I used the below commands to view the synthesized design of multiple_module_opt.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog multiple_module_opt.v
yosys> synth -top multiple_module_opt
yosys> flatten 
yosys> opt_clean -purge
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained optimized design, as we can see 2 and gates and 1 or gate are realized as was expected when optimizations are applied:
	
![Screenshot from 2023-08-12 09-16-59](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/f294addb-43f5-4e33-bbae-1ce231b8906d)


</details>
	
<details>
 <summary> Combinational logic optimizations: multiple_module_opt2.v </summary>
	
I used the below commands to view the synthesized design of multiple_module_opt2.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog multiple_module_opt2.v
yosys> synth -top multiple_module_opt2
yosys> flatten 
yosys> opt_clean -purge
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show

```
	
Below is the screenshot of the obtained optimized design, as we can see no standard cells are realized as was expected when optimizations are applied:
	
![Screenshot from 2023-08-12 16-24-57](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/96042ee3-b427-4634-ad51-242753902118)



</details>
<details>
 <summary> Sequential logic optimizations: dff_const1.v </summary>
	
I used the below commands to simulate the design of dff_const1.v:
	
```bash
iverilog dff_const1.v tb_dff_const1.v
./a.out
gtkwave tb_dff_const1.vcd
```	


Below is the screenshot of the obtained simulation, a we can see even when reset is zero, Q waits for next rising edge of clock:
	
![Screenshot from 2023-08-12 16-28-42](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/61f3a8e3-b388-4e3b-813a-f7e42ab3a7d6)
	
I used the below commands to view the synthesized design of dff_const1.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_const1.v
yosys> synth -top dff_const1
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	

Below is the screenshot of the obtained optimized design:
	
![Screenshot from 2023-08-12 16-34-06](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/6608c051-3de5-4318-8b1d-303a42ba7b0d)

</details>
	
<details>
 <summary> Sequential logic optimizations: dff_const2.v </summary>
	
I used the below commands to simulate the design of dff_const2.v:
	
```bash
iverilog dff_const2.v tb_dff_const2.v
./a.out
gtkwave tb_dff_const2.vcd
```	

Below is the screenshot of the obtained simulation, as we can see Q is one regardless of the value of reset and clock:
	
![Screenshot from 2023-08-12 16-36-27](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/63f2b950-f3e6-4bdd-afec-0c9bbfd136fe)


I used the below commands to view the synthesized design of dff_const2.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_const2.v
yosys> synth -top dff_const2
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained optimized design:

![Screenshot from 2023-08-12 16-41-06](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/424636c5-b075-4df0-9ac1-9f1dc57a38f6)



</details>

	
<details>
 <summary> Sequential logic optimizations: dff_const3.v </summary>
	
I used the below commands to simulate the design of dff_const3.v:
	

```bash
iverilog dff_const3.v tb_dff_const3.v
./a.out
gtkwave tb_dff_const3.vcd
```	

Below is the screenshot of the obtained simulation, as we can see Q does not follow Q1 immediately:
	
![Screenshot from 2023-08-12 16-44-42](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/61227eba-c821-40d2-b00c-2f12ac723a9a)

I used the below commands to view the synthesized design of dff_const3.v:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_const3.v
yosys> synth -top dff_const3
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained design, the 2 flipflops are retained and optimization could not remove any of them:


![Screenshot from 2023-08-12 16-59-59](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/dba0bec6-8254-473c-b478-72e99efdf94c)


</details>
	
<details>
 <summary> Sequential logic optimizations: dff_const4.v </summary>
	
I used the below commands to simulate the design of dff_const4.v:
	
```bash
iverilog dff_const4.v tb_dff_const4.v
./a.out
gtkwave tb_dff_const4.vcd
```	


Below is the screenshot of the obtained simulation, as we can see Q and Q1 are one regardless of clk and reset:

![Screenshot from 2023-08-12 17-25-23](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/eb6ec055-09a5-41b6-bd30-93554ea622cf)
	
I used the below commands to view the synthesized design of dff_const4.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_const4.v
yosys> synth -top dff_const4
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained optimized design, and no hardware was used as expected:
	
![Screenshot from 2023-08-12 17-29-44](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/ce53a32e-a1fb-4415-9ea9-a187158aa16f)


</details>
	
<details>
 <summary> Sequential logic optimizations: dff_const5.v </summary>
	
I used the below commands to simulate the design of dff_const5.v:
	
```bash
iverilog dff_const5.v tb_dff_const5.v
./a.out
gtkwave tb_dff_const5.vcd
```	

Below is the screenshot of the obtained simulation, as we can see when reset is zero, Q1 becomes one on the next rising edge of clk, and Q follows Q1 on the next rising edge of clk:

![Screenshot from 2023-08-12 17-34-10](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/3e61a38a-5c13-4dc1-b633-4f9fe7e24ea5)

	
I used the below commands to view the synthesized design of dff_const5.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog dff_const5.v
yosys> synth -top dff_const5
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```

	
Below is the screenshot of the obtained optimized design, and the 2 flipflops are retained:
	
![Screenshot from 2023-08-12 17-43-09](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/cb1fdf3d-1786-4acf-b48f-e54dc5a49be1)

</details>
	
<details>
 <summary> Sequential logic optimizations for unused outputs: counter_opt.v </summary>
	
I used the below commands to view the synthesized design of counter_opt.v with optimizations:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog counter_opt.v
yosys> synth -top counter_opt
yosys> dfflibmap -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> show
```
	
Below is the screenshot of the obtained optimized design, and the only used output (count[0]) is present and 1 flipflop is used:
	
![Screenshot from 2023-08-12 18-10-14](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/3237d231-7218-4086-a2f3-354c0034c0c5)
	
</details>
	
## Day 4

<details>
 <summary> Summary </summary>

I have performed Gate Level Simulation (GLS). GLS is when the testbench is run with the netlist as design under test to ensure there are no synthesis and simulation mismatches, and it is important as it 1-) verifies the logical correctness of the post-synthesis design and 2-) ensures the timing of design is met. Synthesis and simulation mismatches can happen due to a lot of reasons including missing sensitivity list (some signal changes are not captured by the circuit because they are missing from the sensitivity list), blocking vs non-blocking assignments (inside an always block, "=" statements inside it are blocking meaning they are executed in order they are written, assignments (<=) on the other hand are non-blocking so they are executed in parallel => non-blocking should be used with sequential circuits. Note that the synthesis will yield same circuit with blocking and non-blockin; it will yield what would be obtained as if the statements where written in non-blocking format, so in case they weren't written as such a mismatch will occur with the simulation), and non-standard verilog coding.
	
</details>
	
<details>
 <summary> Verilog codes </summary>
The verilog codes (*_mux.v and blocking_caveat.v) are taken from https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git

</details>
	
<details>
 <summary> Simulation, synthesis, and GLS: ternary_operator_mux.v </summary>

I used the below commands to simulate the design of ternary_operator_mux.v:
	
```bash
iverilog ternary_operator_mux.v tb_ternary_operator_mux.v
./a.out
gtkwave tb_ternary_operator_mux.vcd
```	

Below is the screenshot of the obtained simulation, we can see that when sel is high y follows i1, and when sel is low y follows i0:

![Screenshot from 2023-08-12 21-22-19](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/4400bf28-fdbb-4de0-be02-f3698d2c6bbe)



I used the below commands to synthesize the design into a netlist and view the synthesized design of ternary_operator_mux.v:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog ternary_operator_mux.v
yosys> synth -top ternary_operator_mux
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> write_verilog -noattr ternary_operator_mux_net.v
yosys> show
```
	
Below is the screenshot of the obtained design:
![Screenshot from 2023-08-12 21-26-52](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/e38d5c5e-d9ec-4c3f-a5e1-19f73f6c81ac)


Below is the screenshot of the obtained netlist:
	
![Screenshot from 2023-08-12 21-28-08](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/1cefa0d6-6534-4c9c-a222-41f104035080)


I used the below commands to carry out GLS of ternary_operator_mux.v:
	
```bash
iverilog ../my_lib/verilog_model/primitives.v ../my_lib/verilog_model/sky130_fd_sc_hd.v ternary_operator_mux_net.v tb_ternary_operator_mux.v
./a.out
gtkwave tb_ternary_operator_mux.vcd
```	
	
Below is the screenshot of the obtained simulation, and this matches with pre-synthesis simulation:
	

![Screenshot from 2023-08-15 13-41-51](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/c896c84d-4288-48ff-8ba8-c51ae6ade783)


</details>

<details>
 <summary> Simulation, synthesis, and GLS: bad_mux.v </summary>

I used the below commands to simulate the design of bad_mux.v:
	
```bash
iverilog bad_mux.v tb_bad_mux.v
./a.out
gtkwave tb_bad_mux.vcd
```	

Below is the screenshot of the obtained simulation, we can see that when inputs change, y is not evaluated which is wrong behavior:

![Screenshot from 2023-08-15 13-45-44](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/117bfe93-b07e-4453-8059-bddbb3d2301f)


I used the below commands to synthesize the design into a netlist and view the synthesized design of bad_mux.v:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog bad_mux.v
yosys> synth -top bad_mux
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> write_verilog -noattr bad_mux_net.v
yosys> show
```
	

Below is the screenshot of the obtained design:

![Screenshot from 2023-08-15 13-52-06](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/20ad183f-5550-4ba5-9886-f5a4468c0a1a)

	
Below is the screenshot of the obtained netlist:

![Screenshot from 2023-08-15 13-53-45](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/b6deaf42-c5f6-4359-9703-6a37a34d8cbc)

	
I used the below commands to carry out GLS of bad_mux.v:
	
```bash
iverilog ../my_lib/verilog_model/primitives.v ../my_lib/verilog_model/sky130_fd_sc_hd.v bad_mux_net.v tb_bad_mux.v
./a.out
gtkwave tb_bad_mux.vcd
```	
	
Below is the screenshot of the obtained simulation, and this mismatches with pre-synthesis simulation:
	

![Screenshot from 2023-08-15 13-58-36](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/33535711-8677-44b9-8804-66f122a3b1c7)

	
</details>

<details>
 <summary> Simulation, synthesis, and GLS: blocking_caveat.v </summary>

I used the below commands to simulate the design of blocking_caveat.v:
	

```bash
iverilog blocking_caveat.v tb_blocking_caveat.v
./a.out
gtkwave tb_blocking_caveat.vcd
```	

Below is the screenshot of the obtained simulation, and as we can see d is seeing the precious values, and hence it is acting as if there was a flop in the circuit which is not the case (incorrect behavior):

![Screenshot from 2023-08-15 15-59-20](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/948759c2-8909-462f-92d1-eb158e02d53a)


I used the below commands to synthesize the design into a netlist and view the synthesized design of blocking_caveat.v:
	
```bash
yosys> read_liberty -lib /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> read_verilog blocking_caveat.v
yosys> synth -top blocking_caveat
yosys> abc -liberty /home/malobi/Verilog/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
yosys> write_verilog -noattr blocking_caveat_net.v
yosys> show
```
	
Below is the screenshot of the obtained design:

![Screenshot from 2023-08-15 16-06-10](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/c95de4ee-f793-46c5-95c3-437632131483)
	
Below is the screenshot of the obtained netlist:

![Screenshot from 2023-08-15 16-08-29](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/7346ed17-8ffc-434e-b89d-81893625b835)


I used the below commands to carry out GLS of blocking_caveat.v:
	
```bash
iverilog ../my_lib/verilog_model/primitives.v ../my_lib/verilog_model/sky130_fd_sc_hd.v blocking_caveat_net.v tb_blocking_caveat.v
./a.out
gtkwave tb_blocking_caveat.vcd

```	
	
Below is the screenshot of the obtained simulation, and this mismatches with pre-synthesis simulation due to blocking statement:
	

![Screenshot from 2023-08-15 16-12-58](https://github.com/malobimukherjee/MALOBIMUKHERJEE/assets/141206513/7029e320-d8eb-4ecd-a26d-6b710aa2710d)
	
</details>
