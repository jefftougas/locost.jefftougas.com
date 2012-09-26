Command to get nice list of images in directory:

find images | grep jpg | sed 's/.*\/\(.*\)\.jpg/  - \1/'
