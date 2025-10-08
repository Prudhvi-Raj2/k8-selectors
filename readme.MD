tainted Nodes:
=================
kubectl taint nodes ip-192-168-57-72.ec2.internal hardware=gpu:NoSchedule --recent
kubectl taint nodes ip-192-168-60-83.ec2.internal harware=nothing:NoExecute
kubectl taint nodes ip-192-168-57-72.ec2.internal hardware=something:NoExecute --recent
