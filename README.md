
# Training project (HTML-CSS & DOCPAD & JAVASCRIPT)

## Setup

Install:

  1. Installing Virtualbox:
  ``` 
  $ sudo apt-get install virtualbox
  ```
  
  2. Installing Vagrant:
  ```
  $ sudo apt-get install vagrant
  ```

  3. Getting vagrant  machine up:
  ```
  $ vagrant box add precise32 http://files.vagrantup.com/precise32.box
  ```

  4. Configure Project:
  ```
  $ mkdir vagrant_project
  $ cd vagrant_project
  $ vagrant init
  ```

  5. Edit the Vagrantfile in this directory and replace
  ```
  config.vm.box = "precise32"
  ```


Start Server to run DOCPAD:
  ```
  vagrant ssh
  cd /docpad
  docpad run
  ```

Start Server to run HTML-CSS:
  ```
  vagrant ssh
  cd /html-css
  python -m SimpleHTTPServer 4000
  ```

## NOTES

  1. HTML-CSS folder:
    Contain source runing with port: 4000

  2. DOCPAD folder:
    Contain SASS, Jade language
    Docpad will render from SASS to CSS and from Jade to HTML

  3.JAVASCRIPT folder:
    Learning JavaScript
## MY PRACTICE
  1. Run
    ```
    cd /DOCPAD/practices/greensbury-fix
    docpad run
    ```
   
  2. Dir: DOCPAD/practices/greensbury-fix
  3. File name:
    index.html
    contact.html
    list-products.html
    product-details.