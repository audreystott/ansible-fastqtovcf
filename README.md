# Automated FastQ-to-VCF tools deployment

The FastQ-to-VCF pipeline incorporates two pipelines from the Sydney Informatics Hub: [Fastq-to-BAM](https://github.com/Sydney-Informatics-Hub/Fastq-to-BAM) and [Germline-ShortV](https://github.com/Sydney-Informatics-Hub/Germline-ShortV).

The automated deployment of tools for the FastQ-to-VCF pipeline consist of first checking if the tools are available as modules on the central system, and to automatically install those that are not.

### Git clone this repository
	
	git clone https://github.com/audreystott/ansible-fastqtovcf.git
	cd ansible-fastqtovcf


### Run the following Ansible script

	ansible-playbook tools-install.yaml –i vars_list_tools



