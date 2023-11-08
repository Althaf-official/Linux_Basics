   # What is the home directory for the user called bob?
   echo $HOME
  145  # Which of the following commands will show you your home directory?

  # In the command echo Welcome, what does the word Welcome represent with respect to the command?
  147  ## argument
   # What type of command is git?

  ## file
# Now, lets create some directories! Refer to the below diagram and create the directory called birds
  153  ls
  154  pwd
  155  mkdir birds
  156  mkdir /home/bob/fish/salmon
  157  # Next, create the directories /home/bob/fish/salmon
  158  mkdir  -p /home/bob/fish/salmon
  159  mkdir  -p /home/bob/fish/salmon
  160  mkdir -p /home/bob/mammals/monkey
  161  mkdir -p /home/bob/mammals/elephant
  162  mkdir /home/bob/birds/eagle
  163  mkdir -p /home/bob/reptile/snake
  164  mkdir -p /home/bob/reptile/frog
  165  mkdir -p /home/bob/amphibian/salamander


  
# Moving along. Lets now move the directory called frog from reptile to the directory amphibian
 mv /home/bob/reptile/frog /home/bob/amphibian

 
 # Next, rename the directory snake to crocodile
  mv /home/bob/reptile/snake /home/bob/reptile/crocodile

  
  # Finally, delete the directory called reptile along with its contents.
  rm -r /home/bob/reptile
