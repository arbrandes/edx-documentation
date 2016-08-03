.. _Word Cloud:

##################
Word Cloud Tool
##################

.. note:: EdX offers provisional support for this tool.

In a word cloud, learners enter words into a field in response to a question
or prompt. The words that all of the learners enter then appear instantly as a
colorful graphic, with the most popular responses appearing largest. The
graphic becomes larger as more learners answer. Learners can see how their
peers answered as well as contribute their thoughts to the group.

For example, the following word cloud was created from learners' responses to
a question about why they think addressing climate change is difficult.

.. image:: ../../../shared/images/WordCloudExample.png
  :alt: Image of a word cloud problem.

.. contents::
   :local:
   :depth: 2

************************************************
Enable the Word Cloud Tool
************************************************

Before you can add a word cloud to your course, you must enable the word cloud
tool.

To enable the word cloud tool in Studio, you add the ``"word_cloud"`` key to
the **Advanced Module List** on the **Advanced Settings** page. (Be sure to
include the quotation marks around the key value.) For more information, see
:ref:`Enable Additional Exercises and Tools`.

****************************
Create a Word Cloud
****************************

To create a word cloud, follow these steps.

#. In the unit where you want to create the problem, select **Advanced**
   under **Add New Component**.
#. In the list of problem types, select **Word Cloud**.
#. In the component that appears, select **Edit**.
#. In the component editor, specify these settings.

   * **Display Name**: The name you give to this word cloud; this name appears
     as a heading above the problem.
   * **Inputs**: The number of text boxes provided for learners to enter words,
     phrases, or sentences.
   * **Instructions**: The instructions, or prompt for this word cloud. Replace
     the text in this field with specific instructions for this word cloud.
   * **Maximum Words**: The maximum number of words that the word cloud
     displays. If learners enter 300 different words but the maximum is set to
     250, only the 250 most commonly entered words appear in the word cloud.
   * **Show Percents**: The number of times that learners have entered a given
     word as a percentage of all words entered appears near that word.

#. Select **Save**.
