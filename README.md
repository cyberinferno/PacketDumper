# Packet Dumper

A simple Microsoft detour based packet logging DLL written using C++ which hooks into **Ws2_32.send** as well as **Ws2_32.recv** of a target application.

It logs packet into a folder name **PacketLog** in the parent directory where the injected executable is situated.

## Usage

* Build the solution using Visual Studio 2017.
* Inject PacketDumper.dll into the target process using your favourite DLL injection tool such as DLLInjector.