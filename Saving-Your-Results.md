## 7-i. Saving a Copy of Your Results to Take Home With You

If you are performing this tutorial on a cloud instance, everything will be deleted when the instance is destroyed! To package and download everything used or created during the tutorials you can do the following from your cloud terminal session.

First package and compress all of the directories and files in the ‘rnaseq’ directory

```bash

cd /home/ubuntu/workspace/
tar -czvf rnaseq_tutorial.tar.gz rnaseq/

```

Now you can download this to your own computer from here:
 * http://__YOUR_IP_ADDRESS__/workspace/rnaseq_tutorial.tar.gz
	
To unpack this archive at a terminal session on your own Linux or Mac computer you can do the following:

```bash

tar -xzvf rnaseq_tutorial.tar.gz

```

| [[Previous Section\|Trinotate-Functional-Annotation]]       | [[This Section\|Saving-Your-Results]]   | [[Next Section\|Abbreviations]]  |
|:------------------------------------------------------------:|:---------------------------:|:------------------------------:|
| [[Trinotate\|Trinotate-Functional-Annotation]] | [[Saving Results\|Saving-Your-Results]]       | [[Abbreviations\|Abbreviations]] |
