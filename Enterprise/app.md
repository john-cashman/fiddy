.. _enterprise-app:

# FiftyOne Enterprise App
.. default-role:: code

The FiftyOne Enterprise App allows you to visualize, browse, and interact with your
individual datasets like you can with the [FiftyOne App](fiftyone-app),
but with expanded features for organizing, permissionsing, versioning, and
sharing your team's datasets, all from a centralized web portal.

This page provides a brief overview of some features available only in the
FiftyOne Enterprise App.

.. _enterprise-homepage:

### The homepage
When you login to the FiftyOne Enterprise App, you'll land on the homepage pictured
below.

In the top bar of this page, on the left side, the gray number next to
"All datasets" indicates the total number of datasets that you have access to.
If there are more than 20 datasets, you can use the "Previous" and "Next"
buttons at the bottom of the page to see different batches of datasets.

{% hint style="info" %}
You can return to the homepage from any page of the Enterprise App by clicking on
{% endhint %}
   the Voxel51 logo in the upper left corner.

<figure><img src="/images/enterprise/homepage.png" alt="app-homepage"><figcaption></figcaption></figure>

.. _enterprise-pinned-datasets:

## Pinned datasets
You can pin datasets for easy access by hovering over the dataset's name in
the main table and clicking the pin icon.

The "Your pinned datasets" widget on the right-hand side of the hompage shows
your pinned datasets at a glance and allows you to quickly open one by
clicking on its name. Pinned datasets are listed in reverse chronological order
(most recently pinned on top).

To unpin a dataset, click the pin icon next to the dataset name in the "Your
pinned datasets" widget or the pin next to the dataset's name in the main
table.

<figure><img src="/images/enterprise/pinned_datasets.png" alt="pin-datasets"><figcaption></figcaption></figure>
   :width: 500

.. _enterprise-sorting-datasets:

## Sorting datasets
You can use the drop-down menu in the upper left of the main table to sort your
datasets by various criteria, including size, creation date, recently used, and
alphabetically by name:

<figure><img src="/images/enterprise/ordering_datasets.png" alt="order-datasets"><figcaption></figcaption></figure>
   :width: 500

.. _enterprise-filtering-datasets:

## Filtering datasets
You can use the search bar (with the magnifying glass icon) in the upper right
corner of the dataset table to filter datasets by name, tags, and media type:

<figure><img src="/images/enterprise/dataset_search_bar.png" alt="dataset-search-bar"><figcaption></figcaption></figure>
   :width: 500

By default, datasets that match across any supported field are returned, but
you can narrow the search to specific fields by selecting the relevant option
in the search dropdown:

<figure><img src="/images/enterprise/dataset_search_fields.png" alt="dataset-search-fields"><figcaption></figcaption></figure>
   :width: 500

.. _enterprise-creating-datasets:

### Creating datasets
To create a new dataset, click on the "New dataset" button in the upper right
corner of the homepage. A pop-up will appear allowing you to choose a name,
description, and tags for the dataset:

*  **Name**: as you’re typing a name for your dataset, a URL will appear below
   denoting the address at which the dataset will be accessible. If the name or
   URL is not available, you will be prompted to try another name.

*  **Description**: an optional free text description that you can use to store
   relevant information about your dataset.

*  **Tags**: an optional list of tag(s) for your dataset. For example, you may
   want to record the media type, task type, project name, or other pertinent
   information. To add a tag, type it in the text bar. If you have previously
   used a tag, it will automatically appear in a dropdown and you can select
   it. To add a new tag, type tab or comma.

{% hint style="info" %}
A dataset's name, description, and tags can be edited later from the
{% endhint %}
   dataset's [Manage tab](enterprise-managing-datasets).

<figure><img src="/images/enterprise/create_dataset.png" alt="create-dataset"><figcaption></figcaption></figure>

{% hint style="info" %}
What next? Use the [Enterprise Python SDK](enterprise-python-sdk) to upload new
{% endhint %}
   samples, labels, and metadata to your dataset. A common approach is to
   automate this process via [cloud functions](enterprise-cloud-functions).

.. _enterprise-using-datasets:

### Using a dataset
Click on a dataset from the homepage to open the dataset's "Samples" tab.

From the Samples tab you can visualize, tag, filter, and explore your dataset
just as you would via the [FiftyOne App](fiftyone-app).

<figure><img src="/images/enterprise/samples_page.png" alt="samples-page"><figcaption></figcaption></figure>

{% hint style="info" %}
Did you know? You can also navigate directly to a dataset of interest by
{% endhint %}
   pasting its URL into your browser's URL bar.

.. _enterprise-managing-datasets:

### Managing a dataset
The FiftyOne Enterprise App provides a number of options for managing existing
datasets, as described below.

You can access these options from the [Samples tab](enterprise-using-datasets)
by clicking on the "Manage" tab in the upper left corner of the page.

You can also directly navigate to this page from the
[homepage](enterprise-homepage) by clicking the three dots on the
right hand side of a row of the dataset listing table and selecting
"Edit dataset".

{% hint style="info" %}
Did you know? You can also use the [Enterprise SDK](enterprise-python-sdk) to
{% endhint %}
   programmatically, create, edit, and delete datasets.

.. _enterprise-dataset-basic-info:

## Basic info
The "Basic info" tab is accessible to all users with
[Can view](enterprise-can-view) access to the dataset.

Users with [Can manage](enterprise-can-manage) permissions on the dataset can
edit the name, description, and tags of a dataset from this page.

Additionally, members can create a copy of the dataset by clicking on the
"Clone this dataset" button.

<figure><img src="/images/enterprise/dataset_basic_info.png" alt="dataset-basic-info"><figcaption></figcaption></figure>

.. _enterprise-dataset-access:

## Access
The "Access" tab is only accessible to users with
[Can manage](enterprise-can-manage) permissions on the dataset.

From this tab, users can add, remove, edit, or invite users to the dataset.
Refer to [this page](enterprise-permissions) for more information about the
available dataset-level permissions that you can grant.

<figure><img src="/images/enterprise/dataset_access.png" alt="dataset-access"><figcaption></figcaption></figure>

.. _enterprise-dataset-danger-zone:

## Danger zone
The "Danger zone" tab is only accessible to users with
[Can manage](enterprise-can-manage) permissions on the dataset.

From this tab, you can select "Delete entire dataset" to permanently delete a
dataset from your Enterprise deployment. You must type the dataset's full name in
the modal to confirm this action.

<figure><img src="/images/enterprise/dataset_danger_zone.png" alt="danger-zone"><figcaption></figcaption></figure>

.. warning::

   Deleting a dataset is permanent!
