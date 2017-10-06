
### config-manager-cli 
Edit any config file with one command

----------
 examples of use: 	
 
`$ config hyper.js`  
`$ config hype`  
`$ config hy`

### Usage
 `$ config [arg]`  


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

#### Add config files

`$ ln ~/[your_config_file] ~/.personal_config/[your_config_file]`

example:

`$ ln ~/.vimrc ~/.personal_config/vimrc`
 


