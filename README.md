в соответствии с .gitignore в каталоге .terraform будут игнорироваться:
*.tfvars //все файлы с разрешением .tfvars

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf // конкретный файл
override.tf.json // конкретный файл
*_override.tf // все файлы соотв regexp *_override.tf
*_override.tf.json // все файлы соотв regexp *_override.tf.json

# Include override files you do wish to add to version control using negated pattern
#
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc // конкретный файл
terraform.rc // конкретный файл
