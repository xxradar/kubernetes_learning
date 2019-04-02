# kuberneteslearning

radarhack-pod --> no labels<br>
     you can label a pod via: <code>kubectl label pods radarhack-pod pod=radarhack</code><br>
radarhack-pod2 --> no labels<br>
radarhack-pod3 --> includes a label<br>
radarhack-pod4 --> includes a label, also includes running TCPdump container<br>
     you can view tcpdump output:   <code>kubectl attach radarhack-pod4 -c tcpdump </code> (might need to press enter)<br>
 <br>
 <br>
 <code> kubectl run   -it  --image=busybox sh  </code>
     
