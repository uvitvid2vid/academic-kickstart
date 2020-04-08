+++
# Gallery section using the Blank widget and Gallery element (shortcode).
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

title = "Abstract"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 5

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false
+++


Existing unsupervised video-to-video translation methods fail to produce translated videos which are frame-wise realistic, semantic information preserving and video-level consistent. In this work, we propose a novel unsupervised video-to-video translation model. Our model decomposes the style and the content, uses the specialized encoder-decoder structure and propagates the inter-frame information through bidirectional recurrent neural network (RNN) units. The style-content decomposition mechanism enables us to achieve long-term style-consistent video translation results as well as provides us with a good interface for modality flexible translation. In addition, by changing the input frames and style codes incorporated in our translation, we propose a video interpolation loss, which captures temporal information within the sequence to train our building blocks in a self-supervised manner. Our model can produce photo-realistic, spatio-temporal consistent translated videos in a multimodal way. Subjective and objective experimental results validate the superiority of our model over existing methods.


### UVIT: Multi-subdomain & Multimodality

{{< figure library="true" src="avatar.jpg"  width="1000" height="500" title="We exploit the video temporal information in order to produce multi-subdomain (day, night, snow, etc) videos with different modalities per sub-domain in consistent video-to-video translations." lightbox="true" >}}

### UVIT: Overview 


{{< figure library="true" src="Overviewv3.png"  width="1000" height="500" title="Given an input video sequence, we first decompose it to the content by a Content Encoder and the style by a Style Encoder. Then the content is processed by special RNN units, namely TrajGRUs in order to get the content used for translation and interpolation in a recurrent manner. Finally, the translation content and the interpolation content are decoded to the translated video and the interpolated video together with the style latent variable. We also show the video adversarial loss, the cycle consistency loss, the video interpolation loss and the style encoder loss" lightbox="true" >}}



### UVIT: video translation and video interpolation

{{< figure library="true" src="translation_process_v3.png"  width="1000" height="500" title="Given an input video sequence, we first decompose it to the content by a Content Encoder and the style by a Style Encoder. Then the content is processed by special RNN units, namely TrajGRUs in order to get the content used for translation and interpolation in a recurrent manner. Finally, the translation content and the interpolation content are decoded to the translated video and the interpolated video together with the style latent variable. We also show the video adversarial loss, the cycle consistency loss, the video interpolation loss and the style encoder loss" lightbox="true" >}}



@article{example2, title = {An example journal article}, author={Bighetti, Nelson and Ford, Robert}, journal = {Journal of Source Themes}, year = 2015, volume = 1, number = 1 }
