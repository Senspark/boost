#Prebuild android lib
https://github.com/Manromen/Boost-for-Android/releases

#Install boost bcp tool
brew install boost-bcp

#Extract header  file
bcp --boost=/Users/kiet/Downloads/BOOST-BUILD/Boost-for-Android-master/boost_1_68_0 boost/thread.hpp boost/interprocess/sync/interprocess_mutex.hpp boost/asio.hpp ./out_put_dir

