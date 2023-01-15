 Assume the lateral and longitudinal OTG velocity components of the host vehicle are $v$ and $u$, respectively.
 
 The object being observed also has lateral and longitudinal OTG velocity components $v_t$ and $u_t$, respectively.
 
 The VCS-aligned azimuth angle $\theta$  to the object is the sum of the boresight angle of the sensor w.r.t. this coordinate
 system and the measured azimuth angle in the sensor’s local coordinates.
 
 Denote the measured range rate of the object as $\dot{R}$.
 
 Then for each detection, we have the following equation

 $[u_t\cos\theta + v_t \sin\theta = \dot{R} + u\cos\theta + v\sin\theta]$

 The equation above is a line in the $u_t - v_t$ plane which is orthogonal
 to the unit vector $[ \cos\theta, \sin\theta ]^T$ (with $(\cdot)^T$
 denoting a transpose), and at a distance from the origin of $\dot{R} + u\cos\theta + v\sin\theta$
 
 An efficient algorithm is used find the area in the $u_t - v_t$ plane where the most lines (approximately)
 intersect. 
 
 Detections corresponding to any lines which don’t
 pass through this area are discarded, and if a large enough fraction of the original
 detections are left, then a raw estimate of the OTG velocity components is obtained by solving a weighted least squres problem



=========================================

$\left[\begin{array}{cc}\cos(\theta_1) & \sin(\theta_1) \\\vdots    &      \vdots     \\\cos(\theta_n) & \sin(\theta_n) \end{array}\right]$
$\left[\begin{array}{c}\dot{x} \\\dot{y} \end{array}\right]$ =
$\left[\begin{array}{c}\dot{r}_1 \\\vdots  \\\dot{r}_n \end{array}\right] $

===============================================

$\left(\frac{a}{b}\right)$

============================================

$\left[\begin{array}{cc}\cos(\theta_1) & \sin(\theta_1) \\\vdots    &      \vdots     \\\cos(\theta_n) & \sin(\theta_n) \end{array}\right]$



$\left[\begin{array}{c}\dot{x} \\\dot{y} \end{array}\right]$ =



$\left[\begin{array}{c}\dot{r}_1 \\ \vdots  \\ \dot{r}_n \end{array}\right] $

=================================


$\left[\begin{array}{cc}\cos(\theta_1) & \sin(\theta_1) \\\vdots    &      \vdots     \\\cos(\theta_n) & \sin(\theta_n) \end{array}\right]$

$\left[\begin{array}{c}\dot{x} \\\dot{y} \end{array}\right]$ =

$\left[\begin{array}{c}\dot{r}_1 \\\vdots  \\\dot{r}_n \end{array}\right] $

