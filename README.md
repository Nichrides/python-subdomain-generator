# python-subdomain-generator


The Subdomain Generator is a Python script that uses Sublist3r to enumerate subdomains for a given domain name, using a list of user-provided seed subdomains and keywords to generate potential subdomains. The script generates a list of potential subdomains using permutations of the seed subdomains and keywords, and then passes this list to Sublist3r to enumerate any additional subdomains that are not already included in the list.
Installation

Before using the script, you will need to install Python 3 and Sublist3r. Here's how to install the dependencies:
Python 3

### Installing Python 4
To install Python 3, go to the Python website and download the appropriate version for your operating system. Follow the installation instructions provided by the installer.

### Installing Sublist3r

To install Sublist3r, you can use the following command:

**pip install sublist3r**

This will install Sublist3r and its dependencies.

### Usage

To use the Subdomain Enumerator, follow these steps:

* Create a CSV file named "seed_subdomains.csv" with a single column named "Subdomains" that contains the seed subdomains you want to use as a starting point for subdomain enumeration. Each seed subdomain should be on a separate row.

* Create a CSV file named "seed_keywords.csv" with a single column named "Keywords" that contains the keywords you want to use to generate potential subdomains. Each keyword should be on a separate row.

Run the "subdomain_enumerator.py" script using the following command:

**python subdomain_enumerator.py**

The script will generate a list of potential subdomains using permutations of the seed subdomains and keywords, and will pass this list to Sublist3r to enumerate any additional subdomains that are not already included in the list.

The script will output a CSV file named "subdomains.csv" that contains the list of enumerated subdomains, including the seed subdomains and any additional subdomains discovered by Sublist3r.

### Contributing

If you find a bug or would like to suggest a new feature, please create a new issue on the GitHub repository. Pull requests are also welcome!
License

The Subdomain Enumerator is licensed under the MIT License. See the LICENSE file for more information.
Acknowledgements
