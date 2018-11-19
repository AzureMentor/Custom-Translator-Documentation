# Release notes

**16 November 18**
* **Raised quotas:** You can now train 10 models simultaneously and deploy 10 models simultaneously. If you require additional deployment or training capacity, please reach out to us.
* **Regional deployment:** We have brought up new environments in each of the North America, Europe and Asia Pacific regions.
  * You can choose the geographic region where your Custom Translator models will be hosted. 
  * If you already have a model deployed, it is in North America. You have 30 days from today to change your default. In a subsequent release after that date, the model will be hosted only in your selected region.
  * If you choose to deploy in multiple regions, a hosting charge will apply to each model and each region it is deployed in, after Microsoft begins billing.
* **Translator Hub migration tool:** We now have the migration feature available for opt-in preview. If you are interested in trying this out, please send us your Translator Hub sign-in email address. You will be able to migrate your projects and documents from the Translator Hub to Custom Translator in 3 steps:
  * Create a Custom Translator account if you haven’t done so already and have it open in a new window.
  * Determine the Translator Hub workspace ID you want to migrate from: visit your Hub home page, choose “Settings” and copy the workspace ID to your clipboard. 
  * In Custom Translator, choose the “Migrate” option, paste the Hub workspace ID you just copied and press Enter.
* **Next-generation MT models:** This week, we announced the availability [next-generation NMT technology](https://blogs.msdn.microsoft.com/translation/2018/11/14/nextgennmt/). You can now train your custom model with baseline models that have significantly better translation in Simplified Chinese and in German, from and to English.
* **Improved Error Messaging:** You will see clearer and more actionable error messages in the Custom Translator portal.  


**25 October 18**
* **Sharing your workspace:** You can now share your workspace with other users. Choose between read only, editor, or full access for each user. 
* **Multiple workspaces:** You can create multiple workspaces. This allows for better organization of projects and documents.  
* **Phrase dictionary:** You may now include phrase dictionaries in the training process. When you include a phrase dictionary in training your model, the phrases listed are translated in the way you specified. The dictionary also holds your Do-Not-Translate phrases. Letting the system learn from your training material in full sentences is generally a better choice than using a dictionary.
* **Sentence dictionary:** The sentence dictionary allows you to specify an exact target translation for a source sentence.
* **Sentence alignment:** Improvements to the sentence alignment process result in more sentences being aligned.  We encourage you to try retraining your systems to take advantage of the additional data that can be aligned now.
* **Chinese TMX files now support zh-CN abbreviation:** You no longer need to replace zh-CN with zh-Hans in Chinese TMX files.
* **Added new languages:** Serbian-Latin and Bosnian.
* UI changes and bug fixes.


**12 June 18**

* **Support for larger corpora:** Corpus documents can now contain more than 100,000 sentences per file
* **Sentence alignment:** Sentence aligner is skipped if the corpus has a .align extension on the file
* **Document types:** .XLSX files are now supported
* **.ZIP files:** All supported document types can be included in .zip files
* **Document naming:** When uploading documents, the document name is optional and is no longer a requirement for archive and combo files
* Other bug fixes and improvements


**7 May 18**<br/>
Documentation added to GitHub
