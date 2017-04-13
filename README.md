# Precompiled-Rsync

<h1> PreCompiled static RSYNC binary for ESXi hosts </h1>

A need came about where we needed to move a VM from one ESXi host to another, but due to system instability we required the use of rsync (and more importantly, it's resume-ability), which is not a part of ESXi

William Lam over at virtuallyGhetto provided the bulk of the [instructions](http://www.virtuallyghetto.com/2011/02/how-to-compile-statically-linked-rsync.html) on how to do this (pay special attention to the rsync command structure on his page, as you'll need the -d dbclient switch as well)

Including the compiled binary here, so you don't need to go through the headache of deploying an old CentOS 3.9 box and rebuild this as I did.

<h2>Helpful Links</h2>

http://vault.centos.org/3.9/

https://download.samba.org/pub/rsync/src/rsync-3.1.2.tar.gz
