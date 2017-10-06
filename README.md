
### config-manager-cli 
Edit any config file with one command

----------
 examples of use: 	
 
`$ config hyper.js`  
`$ config hype`  
`$ config hy`

### Usage
 `$ config [config_name]`  


### Install 

`$ git clone https://github.com/loydle/config-manager-cli.git`

`$ chmod 755 ~/.personal_bin/config`

`$ cp config-manager-cli/.personal_bin ~/.personal_bin `

`$ cp config-manager-cli/.personal_config ~/.personal_config `

`$ vim ~/.bash_script`

add the following line to ~/.bash_profile 

```bash
export PATH=$PATH:.:$HOME/.personal_bin:

```

#### Add own configuration files

`$ ln ~/[path][config_file] ~/.personal_config/[config_file]`

example:

`$ ln ~/.vimrc ~/.personal_config/vimrc`
 


