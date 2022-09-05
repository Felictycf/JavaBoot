mysqldump jeecg-boot -u root -phujian --add-drop-table | mysql zhishi -u root -phujian


我们原本的 jeecg-boot 就源数据库， 之后 zhishi是我们需要复制出来使用的数据库 ，数据库需要初始化，合适多人的使用。
