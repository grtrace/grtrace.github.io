## GRTrace – the General Relativity rayTracer

This is an implementation of the raytracing algorithm we have developed, the rays are casted in a curved spacetime.
The spacetime is specified by either an analytic metric description (e.g. Kerr metric) or a numeric one (not yet implemented).
The path is traced by numerically integrating the 0th geodesic equation using the Runge-Kutta method of 4th order,
curving of light rays and gravitational Doppler effect are taken into account.
GRTrace allows to generate a full image from a specified perspective or to trace single rays and visualise them in a visual helper, implemented as an OpenGL window.

