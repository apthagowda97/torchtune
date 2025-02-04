.. _datasets:

==================
torchtune.datasets
==================

.. currentmodule:: torchtune.datasets


Example datasets
----------------

torchtune supports several widely used datasets to help quickly bootstrap your fine-tuning

.. autosummary::
    :toctree: generated/
    :nosignatures:

    alpaca_dataset
    alpaca_cleaned_dataset
    grammar_dataset
    samsum_dataset
    slimorca_dataset

Generic dataset builders
------------------------

torchtune also supports generic dataset builders for common formats like chat models and instruct models

.. autosummary::
    :toctree: generated/
    :nosignatures:

    instruct_dataset
    chat_dataset
