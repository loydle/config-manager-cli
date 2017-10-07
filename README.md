
# config-manager-cli 
> Edit all your config file in one command  :thumbsup: :sparkles:

 examples of use: 	
 
`$ config hyper.js`  
`$ config hype`  
`$ config hy`

## Usage
 `$ config [config_name]`  


## Install 

`$ git clone https://github.com/loydle/config-manager-cli.git`

`$ chmod 755 ~/.personal_bin/config`

`$ cp config-manager-cli/.personal_bin ~/.personal_bin `

`$ cp config-manager-cli/.personal_config ~/.personal_config `

`$ vim ~/.bash_script`

add the following line to ~/.bash_profile 

```bash
export PATH=$PATH:.:$HOME/.personal_bin:

```

### Add own configuration files

`$ ln ~/[path][config_file] ~/.personal_config/[config_file]`

example:

`$ ln ~/.vimrc ~/.personal_config/vimrc`
 
 ### Done! :beers:
 ------------
 
 ### MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


