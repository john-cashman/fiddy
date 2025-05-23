# Overview

| <p><a href="https://github.com/voxel51/fiftyone"><img src="_static/images/icons/github-logo-256px.png" alt="GitHub repository" data-size="line"><br>View on GitHub</a></p> | <p><a href="https://community.voxel51.com/"><img src="_static/images/icons/discord-logo-256px.png" alt="Discord community" data-size="line"><br>Join us on Discord</a></p> | <p><a href="https://colab.research.google.com/github/voxel51/fiftyone-examples/blob/master/examples/quickstart.ipynb"><img src="_static/images/icons/colab-logo-256px.png" alt="Colab quickstart" data-size="line"><br>Try it in Colab</a></p> |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

**The open-source tool for building high-quality datasets and computer vision models**

Nothing hinders the success of machine learning systems more than poor quality\
data. And without the right tools, improving a model can be time-consuming and\
inefficient.

FiftyOne supercharges your machine learning workflows by enabling you to\
visualize datasets and interpret models faster and more effectively.

{% embed url="https://voxel51.com/images/fiftyone_long_sizzle_light_bg.mp4" %}

Improving data quality and understanding your model's failure modes are the\
most impactful ways to boost the performance of your model.

FiftyOne provides the building blocks for optimizing your dataset analysis\
pipeline. Use it to get hands-on with your data, including visualizing complex\
labels, evaluating your models, exploring scenarios of interest, identifying\
failure modes, finding annotation mistakes, and much more!

<a href="getting_started/install.html" class="button primary">Install FiftyOne!</a>\
FiftyOne integrates naturally with your favorite tools. Click on a logo to\
learn how:

[<img src="https://voxel51.com/images/integrations/pytorch-128.png" alt="PyTorch" data-size="line">](recipes/adding_detections.html)[<img src="https://voxel51.com/images/integrations/pytorch-lightning-128.png" alt="PyTorch Lightning" data-size="line">](integrations/lightning_flash.html)[<img src="https://voxel51.com/images/integrations/hugging-face-128.png" alt="Hugging Face" data-size="line">](integrations/huggingface.html)[<img src="https://voxel51.com/images/integrations/ultralytics-128.png" alt="Ultralytics" data-size="line">](integrations/ultralytics.html)[<img src="https://voxel51.com/images/integrations/super-gradients-128.png" alt="SuperGradients" data-size="line">](integrations/super_gradients.html)[<img src="https://voxel51.com/images/integrations/tensorflow-128.png" alt="TensorFlow" data-size="line">](recipes/adding_detections.html)[<img src="https://voxel51.com/images/integrations/detectron2-128.png" alt="Detectron2" data-size="line">](tutorials/detectron2.html)[<img src="https://voxel51.com/images/integrations/qdrant-128.png" alt="Qdrant" data-size="line">](integrations/qdrant.html)[<img src="https://voxel51.com/images/integrations/redis-128.png" alt="Redis" data-size="line">](integrations/redis.html)[<img src="https://voxel51.com/images/integrations/pinecone-128.png" alt="Pinecone" data-size="line">](integrations/pinecone.html)[<img src="https://voxel51.com/images/integrations/mongodb-128.png" alt="MongoDB" data-size="line">](integrations/mongodb.html)[<img src="https://voxel51.com/images/integrations/elasticsearch-128.png" alt="Elasticsearch" data-size="line">](integrations/elasticsearch.html)[<img src="https://voxel51.com/images/integrations/milvus-128.png" alt="Milvus" data-size="line">](integrations/milvus.html)[<img src="https://voxel51.com/images/integrations/lancedb-128.png" alt="LanceDB" data-size="line">](integrations/lancedb.html)[<img src="https://voxel51.com/images/integrations/activitynet-128.png" alt="ActivityNet" data-size="line">](integrations/activitynet.html)[<img src="https://voxel51.com/images/integrations/coco-128.png" alt="COCO" data-size="line">](integrations/coco.html)[<img src="https://voxel51.com/images/integrations/open-images-128.png" alt="Open Images" data-size="line">](integrations/open_images.html)[<img src="https://voxel51.com/images/integrations/jupyter-128.png" alt="Jupyter" data-size="line">](environments/index.html#notebooks)[<img src="https://voxel51.com/images/integrations/colab-128.png" alt="Google Colab" data-size="line">](environments/index.html#notebooks)[<img src="https://voxel51.com/images/integrations/plotly-128.png" alt="Plotly" data-size="line">](user_guide/plots.html)[<img src="https://voxel51.com/images/integrations/cvat-128.png" alt="CVAT" data-size="line">](integrations/cvat.html)[<img src="https://voxel51.com/images/integrations/labelstudio-128.png" alt="Label Studio" data-size="line">](integrations/labelstudio.html)[<img src="https://voxel51.com/images/integrations/v7-128.png" alt="V7" data-size="line">](integrations/v7.html)[<img src="https://voxel51.com/images/integrations/segments-128.png" alt="Segments" data-size="line">](https://github.com/segments-ai/segments-voxel51-plugin)[<img src="https://voxel51.com/images/integrations/labelbox-128.png" alt="Labelbox" data-size="line">](integrations/labelbox.html)[<img src="https://voxel51.com/images/integrations/scale-128.png" alt="Scale AI" data-size="line">](api/fiftyone.utils.scale.html)[<img src="https://voxel51.com/images/integrations/google-cloud-128.png" alt="Google Cloud" data-size="line">](enterprise/installation.html#google-cloud-storage)[<img src="https://voxel51.com/images/integrations/aws-128.png" alt="Amazon Web Services" data-size="line">](enterprise/installation.html#amazon-s3)[<img src="https://voxel51.com/images/integrations/azure-128.png" alt="Azure" data-size="line">](enterprise/installation.html#microsoft-azure)

{% hint style="info" %}
FiftyOne is growing! [Sign up for the mailing list](https://share.hsforms.com/1zpJ60ggaQtOoVeBqIZdaaA2ykyk)\
to learn about new features as they come out.
{% endhint %}

### Core Capabilities

## Features

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><strong>Curating datasets</strong><br>Surveys show that machine learning engineers spend over half of their time wrangling data, but it doesn't have to be that way. Use FiftyOne's powerful dataset import and manipulation capabilities to manage your data with ease.<br></td><td></td><td><a href="user_guide/dataset_creation/index.html">index.html</a></td></tr><tr><td><strong>Evaluating models</strong><br>Aggregate metrics alone don’t give you the full picture of your ML models. In practice, the limiting factor on your model’s performance is often data quality issues that you need to see to address. FiftyOne makes it easy to do just that.<br></td><td></td><td><a href="tutorials/evaluate_detections.html">evaluate_detections.html</a></td></tr><tr><td><strong>Visualizing embeddings</strong><br>Are you using embeddings to analyze your data and models? Use FiftyOne's embeddings visualization capabilities to reveal hidden structure in you data, mine hard samples, pre-annotate data, recommend new samples for annotation, and more.<br></td><td></td><td><a href="tutorials/image_embeddings.html">image_embeddings.html</a></td></tr><tr><td><strong>Working with geolocation</strong><br>Many datasets have location metadata, but visualizing location-based datasets has traditionally required closed source or cloud-based tools. FiftyOne provides native support for storing, visualizing, and querying datasets by location.<br></td><td></td><td><a href="user_guide/plots.html#geolocation-plots">plots.html</a></td></tr><tr><td><strong>Finding annotation mistakes</strong><br>Annotations mistakes create an artificial ceiling on the performance of your model. However, finding these mistakes by hand is not feasible! Use FiftyOne to automatically identify possible label mistakes in your datasets.<br></td><td></td><td><a href="tutorials/classification_mistakes.html">classification_mistakes.html</a></td></tr><tr><td><strong>Removing redundant images</strong><br>During model training, the best results will be seen when training on unique data. Use FiftyOne to automatically remove duplicate or near-duplicate images from your datasets and curate diverse training datasets from your raw data.<br></td><td></td><td><a href="tutorials/uniqueness.html">uniqueness.html</a></td></tr></tbody></table>

### Core Concepts

## FiftyOne Library

FiftyOne's core library provides a structured yet dynamic representation to\
explore your datasets. You can efficiently query and manipulate your dataset by\
adding custom tags, model predictions and more.

<a href="user_guide/basics.html" class="button primary">Explore the library</a>

```python
import fiftyone as fo
```

```
dataset = fo.Dataset("my_dataset")

sample = fo.Sample(filepath="/path/to/image.png")
sample.tags.append("train")
sample["custom_field"] = 51

dataset.add_sample(sample)

view = dataset.match_tags("train").sort_by("custom_field").limit(10)

for sample in view:
    print(sample)
```

{% hint style="info" %}
FiftyOne is designed to be lightweight and flexible, making it easy to load your datasets. FiftyOne supports loading datasets in a variety of common formats out-of-the-box, and it also provides the extensibility to load datasets in custom formats.\
Check out [loading datasets](user_guide/dataset_creation/index/) to see how to load your data into FiftyOne.
{% endhint %}

## FiftyOne App

The FiftyOne App is a graphical user interface that makes it easy to explore\
and rapidly gain intuition into your datasets. You can visualize labels like\
bounding boxes and segmentations overlaid on the samples; sort, query and\
slice your dataset into any subset of interest; and more.

<a href="user_guide/app.html" class="button primary">See more of the App</a>

<figure><img src="images/homepage_app.png" alt="fiftyone-app"><figcaption></figcaption></figure>

## FiftyOne Brain

The FiftyOne Brain is a library of powerful machine learning-powered\
capabilities that provide insights into your datasets and recommend ways to\
modify your datasets that will lead to measurably better performance of your\
models.

<a href="brain.html" class="button primary">Learn more about the Brain</a>

```python
import fiftyone.brain as fob
```

fob.compute\_uniqueness(dataset)\
rank\_view = dataset.sort\_by("uniqueness")

## FiftyOne Plugins

FiftyOne provides a powerful plugin framework that allows for extending and\
customizing the functionality of the tool to suit your specific needs.

With plugins, you can add new functionality to the FiftyOne App, create\
integrations with other tools and APIs, render custom panels, and add custom\
buttons to menus.

With [FiftyOne Enterprise](enterprise-delegated-operations/), you can even write\
plugins that allow users to execute long-running tasks from within the App that\
run on a connected compute cluster.

<a href="plugins/index.html" class="button primary">Install some plugins!</a>

<figure><img src="images/plugins/operators/examples/embeddings.gif" alt="fiftyone-plugins"><figcaption></figcaption></figure>

## Dataset Zoo

The FiftyOne Dataset Zoo provides a powerful interface for downloading datasets\
and loading them into FiftyOne.

It provides native access to dozens of popular benchmark datasets, and it als\
supports downloading arbitrary public or private datasets whose\
download/preparation methods are provided via GitHub repositories or URLs.

<a href="dataset_zoo/index.html" class="button primary">Check out the Dataset Zoo</a>

```python
import fiftyone as fo
```

```
import fiftyone.zoo as foz

dataset = foz.load_zoo_dataset("coco-2017", split="validation")

session = fo.launch_app(dataset)
```

<figure><img src="images/dataset_zoo_coco_2017.png" alt="dataset-zoo"><figcaption></figcaption></figure>

## Model Zoo

The FiftyOne Model Zoo provides a powerful interface for downloading models and\
applying them to your FiftyOne datasets.

It provides native access to hundreds of pre-trained models, and it also\
supports downloading arbitrary public or private models whose definitions are\
provided via GitHub repositories or URLs.

<a href="model_zoo/index.html" class="button primary">Check out the Model Zoo</a>

```python
import fiftyone as fo
```

```
import fiftyone.zoo as foz

dataset = foz.load_zoo_dataset(
    "coco-2017",
    split="validation",
    max_samples=50,
    shuffle=True,
)

model = foz.load_zoo_model(
    "clip-vit-base32-torch",
    text_prompt="A photo of a",
    classes=["person", "dog", "cat", "bird", "car", "tree", "chair"],
)

dataset.apply_model(model, label_field="zero_shot_predictions")

session = fo.launch_app(dataset)
```

### What's Next?

Where should you go from here? You could...

* [Install FiftyOne](installing-fiftyone/)
* Try one of the [tutorials](tutorials/index/) that demonstrate the unique\
  capabilities of FiftyOne
* Explore [recipes](recipes/index/) for integrating FiftyOne into\
  your current ML workflows
* Check out the [cheat sheets](cheat_sheets/index/) for topics you may\
  want to master quickly
* Consult the [user guide](user_guide/index/) for detailed instructions on\
  how to accomplish various tasks with FiftyOne

### Need Support?

If you run into any issues with FiftyOne or have any burning questions, feel\
free to [connect with us on Discord](https://community.voxel51.com) or reach out to\
us at support@voxel51.com.

## Table of Contents

*   [Overview](self/)

    FiftyOne Enterprise 🚀 \<enterprise/index>\
    Installation \<getting\_started/install>\
    Environments \<environments/index>\
    Tutorials \<tutorials/index>\
    Recipes \<recipes/index>\
    Cheat Sheets \<cheat\_sheets/index>\
    User Guide \<user\_guide/index>\
    Dataset Zoo \<dataset\_zoo/index>\
    Model Zoo \<model\_zoo/index>\
    FiftyOne Brain Integrations \<integrations/index>\
    Plugins \<plugins/index>\
    CLI \<cli/index>\
    API Reference \<api/fiftyone>\
    Release Notes Deprecation Notices FAQ \<faq/index>
