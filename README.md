#ugdir

This shell script for compress each js file of a directory, and output another dircetory.

压缩一个文件夹里所有 js 文件到另一个文件夹。


###Usage

	    ugdir in-dir/path out-dir/path [filter=a.js,b.js] [-warn]
	    
The `filter` js file will copy to the target directory, `-warn` will display warnings when dropping unreachable code or unused declarations etc.

###Installation
	git clone git@github.com:Aben/ugdir.git
	npm install
	npm link # maybe need sudo

