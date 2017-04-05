---
layout: post
title:  "Week 10: Visual presentation"
date:   2017-04-05 10:17
---

It would seem as if this post is a week late, apologies for that. 
During the week work continues on the surface rendering feature. 
Objects should use the particle structure for physics simulation while the
actual object is rendered with a triangle mesh. 

The code restructuring in which we moved from array of structures to structures of arrays 
as completed. We saw a small but pronounced increase in performance. 

The application now also allows for setting the physics timestep explicitly,
rendering the particles in the correct size and rendering a more pleasnt scene.

XPBD was implemented but did not produce the results that was expected.
While it did decouple timestep and #iterations from visual behaviour,
it added more sensitivity to simulation parameters. A decision was made
to postpone merging with the rest of the code.
