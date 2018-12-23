k8s-worker
=========

k8s worker ノードを kubeadm コマンドで導入するAnsible playbook.

Requirements
------------

None.

Role Variables
--------------

- master_ip: masterノードのIPアドレスかホスト名
- k8scluster_token: クラスタにjoinするために必要なトークン. master の init 後にstdoutに出力される.
- k8scluster_cert_hash: ca certのhashキー. master の init 後にstdoutに出力される.


Dependencies
------------

- rasp-docker
- k8s-common

License
-------

BSD

Author Information
------------------

This role was created in 2018 by Hayato Yasuhisa.
