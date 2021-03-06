**To create a lifecycle hook**

This example creates a lifecycle hook::

   aws autoscaling put-lifecycle-hook --lifecycle-hook-name my-lifecycle-hook --auto-scaling-group-name my-auto-scaling-group --lifecycle-transition autoscaling:EC2_INSTANCE_LAUNCHING --notification-target-arn arn:aws:sns:us-west-2:123456789012:my-sns-topic --role-arn arn:aws:iam::123456789012:role/my-auto-scaling-role

For more information, see `Adding Lifecycle Hooks`_ in the *Auto Scaling Developer Guide*.

.. _`Adding Lifecycle Hooks`: http://docs.aws.amazon.com/AutoScaling/latest/DeveloperGuide/adding-lifecycle-hooks.html
