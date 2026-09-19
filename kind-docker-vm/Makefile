common:
	git pull

apply: common
	terraform init
	terraform apply -auto-approve


destroy: common
	terraform init
	terraform destroy -auto-approve