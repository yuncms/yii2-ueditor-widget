# yii2-ueditor-widget

适用于 Yii2 的百度 UEditor

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist yuncms/yii2-ueditor-widget "*"
```

or add

```
"yuncms/yii2-ueditor-widget": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php

<?= $form->field($model, 'content')->widget(\xutl\ueditor\UEditor::className(),[
	//etc...
]) ?>
<?= "<?= \xutl\ueditor\UEditor::widget(); ?>" ?>