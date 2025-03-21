
HingeRadau
^^^^^^^^^^

.. py:method:: Model.beamIntegration("HingeRadau",tag,secI,lpI,secJ,lpJ,secE)
   :noindex:

   Modified two-point Gauss-Radau integration over each hinge region places an integration point at
   the element ends and at :math:`8/3` the hinge length inside the element. 
   This approach represents
   linear curvature distributions exactly and the characteristic length for softening plastic hinges is equal to the assumed palstic hinge length.

   Arguments and examples see :ref:`HingeMidPoint-BeamIntegration`.

