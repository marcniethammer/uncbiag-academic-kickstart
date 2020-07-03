---
title: "Fluid registration between lung CT and stationary chest tomosynthesis images"
date: 2020-01-01
publishDate: 2020-07-03T00:07:50.218136Z
authors: ["Lin Tian", "Connor Puett", "Peirong Liu", "Zhengyang Shen", "Stephen Aylward", "Yueh Lee", "Marc Niethammer"]
publication_types: ["0"]
abstract: "Registration is widely used in image-guided therapy and image-guided surgery to estimate spatial correspondences between organs of interest between planning and treatment images. However, while high-quality computed tomography (CT) images are often available at planning time, limited angle acquisitions are frequently used during treatment because of radiation concerns or imaging time constraints. This requires algorithms to register CT images based on limited angle acquisitions. We, therefore, formulate a 3D/2D registration approach which infers a 3D deformation based on measured projections and digitally reconstructed radiographs of the CT. Most 3D/2D registration approaches use simple transformation models or require complex mathematical derivations to formulate the underlying optimization problem. Instead, our approach entirely relies on differentiable operations which can be combined with modern computational toolboxes supporting automatic differentiation. This then allows for rapid prototyping, integration with deep neural networks, and to support a variety of transformation models including fluid flow models. We demonstrate our approach for the registration between CT and stationary chest tomosynthesis (sDCT) images and show how it naturally leads to an iterative image reconstruction approach."
featured: false
publication: "*Medical Image Computing and Computer Assisted Intervention - MICCAI*"
---
