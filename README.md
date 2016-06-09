# pantherScore
Modified version of pantherScore that used to classify proteins in the Ensembl Compara / TreeFam pipeline

----

This patch is licensed under the GNU General Public License version 2

# Instructions
The version 1.03 of pantherScore can be downloaded from the PantherDB FTP
server, at ftp://ftp.pantherdb.org/hmm_scoring/10.0/1.03/

The patch has to be applied this way:

* `cd $ENSEMBL_DIR`
* `git clone https://github.com/Ensembl/pantherScore`
* `wget ftp://ftp.pantherdb.org/hmm_scoring/10.0/1.03/pantherScore1.03.zip`
* `unzip -d $DEST_DIR pantherScore1.03.zip` 
* `cd $DEST_DIR/pantherScore1.03/`
* `patch -p1 < $ENSEMBL_DIR/pantherScore/pantherScore1.03.patch`

