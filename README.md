Elastic BeanStalk template for Ruby application with high availabliliy and high scalibility feature.


It will auto deploy every commit on github.

All infra is setup under the AWS VPC layer

Autoscalling group configured with multi A-Z

Scalling rule 
  
    CPU Load gretor than 70%  will increase node
    CPU Load less than 10% will decrease node


Using 2 A-z for HA application 1a and 1c
