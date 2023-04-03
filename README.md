# Bivariate Colormaps

## Abstract

Matplotlib is a powerful visualization library widely used in the scientific community. I propose to develop a new feature for Matplotlib that allows users to create and use bivariate colormaps. Currently, Matplotlib provides a wide range of univariate colormaps to represent different types of data. However, there is no built-in support for bivariate colormaps, which are crucial for displaying complex data sets that require the representation of two variables simultaneously. To address this limitation, I propose to combine two univariate colormaps in various ways, such as averaging, blending, or creating a custom mapping function. This feature will enable Matplotlib users to create effective and visually appealing plots for complex data sets. I believe that the addition of bivariate colormaps to Matplotlib will be a significant step forward for data visualization and will benefit a broad range of scientific disciplines.

## Technical Details

### **Project Description**:

The objective of this project is to develop a new feature for Matplotlib that allows the creation of bivariate colormaps. Currently, Matplotlib only supports univariate colormaps, where a single value is used to determine the color of each pixel in an image. However, there are cases where it is useful to represent two variables in a single image, such as when visualizing complex data with both magnitude and phase information. The proposed feature would enable users to specify two input variables and generate a colormap that maps both variables to a color value.

The proposed approach for generating bivariate colormaps involves combining two univariate colormaps. One approach is to simply average the RGBA values from each univariate colormap to generate a new color for each pixel. Another approach is to use weighted average or more complex algorithms like using a radial basis function to map pairs of values to a single color. Furthermore, allowing the user to write their own custom function should also be possible to allow customization for a specific use-case. The resulting bivariate colormap can then be used to visualize data with two variables.

**Note:** The project approach could be altered based on mentor feedback if required.

### **Steps**:

<ul> 
1. Develop the algorithm for generating bivariate colormaps using Matplotlib functions such as ListedColormap, colormap, and rgba_colors.<br>
2. Write unit tests to ensure the algorithm produces accurate and expected results.<br>
3. Implement the new bivariate colormap feature in Matplotlib and integrate it into the library's codebase.<br>
4. Write additional tests to ensure the new feature integrates seamlessly with the rest of Matplotlib's functionality.<br>
5. Use a continuous integration system, to run the tests automatically on each code commit and pull request.<br>
</ul>

### **Testing**:

Unit tests will be written to test the algorithm for generating bivariate colormaps. These tests will ensure that the output of the algorithm is accurate and meets the expected results. Additional tests will also be written to ensure the new feature integrates properly with the rest of the Matplotlib library.

## Schedule of Deliverables

### **List of Deliverables**

<ul>
    1. Design and implement a set bivariate colormaps using the proposed methodology. <br>
    2. Write comprehensive documentation for the Python functionality and the methodology used to design the colormaps. <br>
    3. Write unit tests and integration tests to ensure the correctness and robustness of the package. <br>
    4. Integrate the functionality with matplotlibs code base while ensuring that good coding practices are followed. <br>
    5. Create a blog post for weekly updates on tasks performed during that specific week. <br>
</ul>

### **Community Bonding Period May 4th -> May 28th**

During this period, I will engage with the community to get familiar with the project's codebase, discuss project requirements, and identify potential issues. I will ensure that my build environment is setup and that I am ready for development. Furthermore, I will create an RMD file seperately maintained as a blog. Regular posts would be made to this blog explaining the work that has been done.

### **Phase 1 May 29th -> July 10th**

<ul>
    1. Research on different algorithms and techniques for generating bivariate colormaps. <br>
    2. Implementing a basic version of the bivariate colormap function in Matplotlib that combines two univariate colormaps.<br>
    3. Writing unit tests to ensure that the function works correctly and integrates with the rest of Matplotlib's codebase.<br>
    4. Submitting a progress report at the end of this phase.<br>
</ul>

### **Phase 2 July 14th -> August 21st**

<ul>
    1. Improving and expanding the bivariate colormap function to include different algorithms for combining the two univariate colormaps.<br>
    2. Adding support for different color spaces and data types.<br>
    3. Improving the performance and efficiency of the function.<br>
    4. Writing more unit tests and documentation.<br>
    5. Participating in code reviews and making necessary changes.<br>
    6. Submitting a progress report at the end of this phase.<br>
</ul>

### **Final Week August 21st -> August 28th**
<ul>
    1. Finalizing the implementation of the bivariate colormap function in Matplotlib.<br>
    2. Ensuring that the function works with different types of plots and use cases.<br>
    3. Updating the documentation and providing examples of usage.<br>
    4. Conducting further testing and fixing any bugs or issues that arise.<br>
</ul>

### **After GSoC**
<ul>
    1. Continue Participating in code reviews and making changes as needed. <br>
    2. Fixing issues that I could feasibly tackle. <br>
    3. Creating new PRs for issues that I work on.
</ul>

## Development Experience

I am Arshdeep Singh, and I can be reached at +919815138659 / arsh.official2002@gmail.com / <a href = "https://www.linkedin.com/in/arshdeep-singh-3b7202229/">Linkedin</a> / <a href = "https://github.com/arsh73552">Github</a>. I am currently a Third Year student pursuing a BE in Computer Science.

I have achieved several notable accomplishments in my field, which illustrate my development experience including winning Best Domain Project in MLH Hackhound Hackathon held at SRM University and being a finalist in Techgig Code Gladiator Codeathon 2022 among over 400,000 total participants. I have also acquired some certifications such as Data Analytics Specialization offered by Google and Neural Networks and Deep Learning offered by DeepLearning.ai.

In terms of experience, I was selected for Amazon Machine Learning Summer School, where I gained a deep understanding of techniques such as Supervised, Unsupervised, Sequential and Reinforcement Learning. I also worked with popular Python libraries such as scikit, pytorch, numpy, tensorflow, cv2, etc.

Currently, I am working as a Prism Research Intern @Samsung, where I am collaborating with a team of 4 members to successfully implement a Machine Learning Model for upscaling images by a factor of 4. I have also contributed to the development of the backend for a first-place winning project out of over 250 participating teams in the Hackhound MLH hackathon, where we utilized Node.js, ReactJS, CockroachDB, Twilio, and Cohere to develop a seamless web application for ordering, reservations, and AI-based food recommendations <a href = "https://github.com/arsh73552/unstarve">Project Link</a>. 
One of my most successful projects is the Road Detection from Satellite Images, where I successfully developed a Generative Adversarial Network (GAN) model using U-Net architecture for generating road maps from satellite images using Pytorch. <a href = "https://github.com/arsh73552/MapGeneration">Project Link</a>

Furthermore, most of my projects are published on githib at https://github.com/arsh73552. I've also had some experience contributing to open-source in the past. I worked on an issue in scikit-image where incorrect output was generated for certain methods. I also helped in writing the unit tests to ensure that there wasn't a problem with the new functionality while fixing the bug.

## Motivation Letter

### Why this project?

The bivariate colormaps project is exciting to me because it has the potential to improve the visualization of complex data sets. As someone who has some experience in data science and visualizations, I understand the importance of effective and efficient data representation. Bivariate colormaps have the ability to represent two dimensions of data in a single color map, which can simplify the visualization process and allow for more accurate and intuitive interpretation of the data. Additionally, the project involves working with the matplotlib library, which is a widely used and respected tool for data visualization. Improving the functionality of such a widely used library would have a significant impact on the field of data science and the larger scientific community.

Furthermore, I've gone through the related issues (<a href = "https://github.com/matplotlib/matplotlib/issues/4369">#4369</a> <a href = "https://github.com/matplotlib/matplotlib/issues/8738">#8738</a> <a href = "https://github.com/matplotlib/matplotlib/issues/14168">#14168</a> <a href = "https://github.com/matplotlib/matplotlib/issues/18809">#18809</a>), thoroughly understand the problem statement and feel like this is a problem statement that i could feasibly tackle.

### Other commitments

If selected, I would be treating GSoC with the highest priority. I don't have any commitments for summer 2023 and would be able to devote a significant amount of time to completion of the project Bivariate Colormaps. I would basically be treating this as full-time job and ensuring that the project is integrated with matplotlibs codebase before final evaluation.
