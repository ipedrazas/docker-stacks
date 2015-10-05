# Docker Stacks

[Stacks](https://github.com/State/stacks) it's an Aws CloudFormation stacks management tool. It can generate templates, list, create, delete and update stacks.

To use the docker image

        -> % docker run -it --rm -v /home/ivan/.aws:/root/.aws \
            ipedrazas/stacks stacks --profile default --region eu-west-1 list

            ipedrazas-guestbook-elb        CREATE_COMPLETE
            ipedrazas-kubernetes-elb       CREATE_COMPLETE
            ipedrazas-coreos-compute       UPDATE_COMPLETE
            ipedrazas-coreos-etcd          UPDATE_COMPLETE
            ipedrazas-coreos-etcd-volumes  UPDATE_COMPLETE
            ipedrazas-infra                CREATE_COMPLETE
