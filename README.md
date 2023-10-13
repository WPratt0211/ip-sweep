# IP Sweeper

**IP Sweeper** is a straightforward and lightweight bash script designed for sweeping and logging IP addresses within a network. This tool provides a practical way to discover and document IP addresses associated with a specific network.

## Usage

### Prerequisites

Before using the IP Sweeper tool, ensure that you have the necessary permissions to scan and enumerate IP addresses within the target network.

### Running the Tool

To sweep and log IP addresses in a network, follow these steps:

1. Open a terminal.
2. Navigate to the directory where the IP Sweeper script is located.
3. Run the script with the following command:

```
./ipsweep.sh {IP_HERE} > output.txt
```

Replace `{IP_HERE}` with the network IP address you want to sweep. For example, to sweep the IP addresses in the 192.168.1.0/24 network, you would use:

```
./ipsweep.sh 192.168.1 > output.txt
```

4. After running the script, you can view the results by using the `cat` command on the output file. For instance:

```
cat output.txt
```

This will display the discovered IP addresses.

## Acknowledgments

IP Sweeper offers a straightforward method for IP address discovery and logging within a network. While it may be further enhanced and refined, it serves as a useful exercise for those interested in bash scripting and network scanning for legitimate and authorized purposes.

---

**Please note that using this tool should be done responsibly and only on networks for which you have explicit permission to perform IP address sweeps. Unauthorized scanning can violate legal and ethical standards.**
