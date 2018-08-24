# Machine-Learning-for-IDS
Cloud Computing enables providers to rent out space on their virtual and physical infrastructures. Denial of
Service (DoS) attacks threaten the ability of the cloud to respond to clients' requests, which results in
considerable economic losses. The existing detection approaches are still not mature enough to satisfy a
cloud-based detection system's requirements since they overlook the changing/dynamic environment, that
characterises the cloud as a result of its inherent characteristics. Indeed, the patterns extracted and used by the
existing detection models to identify attacks, are limited to the current VMs' infrastructure but do not
necessarily hold after performing new adjustments according to the pay-as-you-go business model. Therefore,
the accuracy of detection will be negatively affected. Motivated by this fact, we present a new approach for
detecting DoS attacks in a virtualized cloud under changing environment. The proposed model enables
monitoring and quantifying the effect of resources adjustments on the collected data. This helps filter out the
effect of adjustments from the collected data and thus enhance the detection accuracy in dynamic
environments. Our solution correlates as well VMs' application metrics with the actual resources' load, which
enables the hypervisor to distinguish between benignant high load and DoS attacks. It helps also the hypervisor
identify the compromised VMs that try to needlessly consume more resources. Experimental results show that
our model is able to enhance the detection accuracy under changing environments.
