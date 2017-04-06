# api documentation for  [draft-js (v0.10.0)](https://facebook.github.io/draft-js)  [![npm package](https://img.shields.io/npm/v/npmdoc-draft-js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-draft-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-draft-js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-draft-js)
#### A React framework for building text editors.

[![NPM](https://nodei.co/npm/draft-js.png?downloads=true)](https://www.npmjs.com/package/draft-js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-draft-js/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-draft-js_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-draft-js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-draft-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-draft-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/facebook/draft-js/issues"
    },
    "dependencies": {
        "fbjs": "^0.8.7",
        "immutable": "~3.7.4",
        "object-assign": "^4.1.0"
    },
    "description": "A React framework for building text editors.",
    "devDependencies": {
        "babel-core": "^6.8.0",
        "babel-eslint": "^6.1.2",
        "babel-preset-fbjs": "^2.1.0",
        "del": "^2.2.0",
        "envify": "^3.4.0",
        "es6-shim": "^0.34.4",
        "eslint": "^3.0.1",
        "eslint-config-fbjs": "^1.1.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-flowtype": "^2.17.1",
        "eslint-plugin-react": "^5.2.2",
        "fbjs-scripts": "^0.7.0",
        "flow-bin": "^0.32.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.2",
        "gulp-browserify-thin": "^0.1.5",
        "gulp-clean-css": "^2.0.3",
        "gulp-concat-css": "^2.2.0",
        "gulp-derequire": "^2.1.0",
        "gulp-flatten": "^0.2.0",
        "gulp-header": "1.8.2",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.2.0",
        "gulp-util": "^3.0.6",
        "jest": "^15.1.1",
        "react": "^15.0.0-rc.1",
        "react-dom": "^15.0.0-rc.1",
        "run-sequence": "^1.1.2",
        "through2": "^2.0.1",
        "vinyl-buffer": "^1.0.0",
        "webpack-stream": "^3.0.0"
    },
    "devEngines": {
        "node": "4.x || 6.x",
        "npm": "2.x || 3.x"
    },
    "directories": {},
    "dist": {
        "shasum": "29d16191012b932fdab28a9b37ec1538f421abf6",
        "tarball": "https://registry.npmjs.org/draft-js/-/draft-js-0.10.0.tgz"
    },
    "files": [
        "dist/",
        "lib/",
        "LICENSE",
        "PATENTS"
    ],
    "gitHead": "3a46dc8d326f879ef5edf828e11cbb588a4b62a3",
    "homepage": "https://facebook.github.io/draft-js",
    "jest": {
        "automock": true,
        "rootDir": "./",
        "scriptPreprocessor": "scripts/jest/preprocessor.js",
        "setupFiles": [
            "node_modules/fbjs-scripts/jest/environment.js"
        ],
        "modulePathIgnorePatterns": [
            "<rootDir>/lib/",
            "<rootDir>/node_modules/"
        ],
        "preprocessorIgnorePatterns": [
            "<rootDir>/node_modules/"
        ],
        "testPathDirs": [
            "<rootDir>/src/"
        ],
        "unmockedModulePathPatterns": [
            "<rootDir>/node_modules/fbjs/node_modules/",
            "<rootDir>/node_modules/fbjs/lib/UserAgent.js",
            "<rootDir>/node_modules/fbjs/lib/UserAgentData.js",
            "<rootDir>/node_modules/fbjs-scripts/",
            "<rootDir>/node_modules/immutable/",
            "<rootDir>/node_modules/object-assign/",
            "<rootDir>/node_modules/react/",
            "<rootDir>/node_modules/react-dom/"
        ]
    },
    "keywords": [
        "draftjs",
        "editor",
        "react",
        "richtext"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/Draft.js",
    "maintainers": [
        {
            "name": "fb",
            "email": "opensource+npm@fb.com"
        },
        {
            "name": "flarnie",
            "email": "flarnie.npm@gmail.com"
        },
        {
            "name": "hellendag",
            "email": "isaac@fb.com"
        },
        {
            "name": "tylercraft",
            "email": "tyler@tylercraft.com"
        },
        {
            "name": "zpao",
            "email": "paul@oshannessy.com"
        }
    ],
    "name": "draft-js",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-rc",
        "react-dom": "^0.14.0 || ^15.0.0-rc"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/draft-js.git"
    },
    "scripts": {
        "build": "gulp",
        "flow": "flow src",
        "lint": "eslint .",
        "postbuild": "node node_modules/fbjs-scripts/node/check-lib-requires.js lib",
        "prepublish": "npm run build",
        "pretest": "node node_modules/fbjs-scripts/node/check-dev-engines.js package.json",
        "test": "NODE_ENV=test jest",
        "test-ci": "NODE_ENV=test npm run lint && npm run flow && npm run test"
    },
    "version": "0.10.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module draft-js](#apidoc.module.draft-js)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>CharacterMetadata ()](#apidoc.element.draft-js.CharacterMetadata)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>CompositeDecorator (decorators)](#apidoc.element.draft-js.CompositeDecorator)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>ContentBlock ()](#apidoc.element.draft-js.ContentBlock)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>ContentState ()](#apidoc.element.draft-js.ContentState)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorContents_react ()](#apidoc.element.draft-js.DraftEditorContents_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorLeaf_react ()](#apidoc.element.draft-js.DraftEditorLeaf_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorPlaceholder_react ()](#apidoc.element.draft-js.DraftEditorPlaceholder_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorTextNode_react (props)](#apidoc.element.draft-js.DraftEditorTextNode_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>Editor (props)](#apidoc.element.draft-js.Editor)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>EditorBlock ()](#apidoc.element.draft-js.EditorBlock)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>EditorState (immutable)](#apidoc.element.draft-js.EditorState)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>EntityInstance ()](#apidoc.element.draft-js.EntityInstance)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>SelectionState ()](#apidoc.element.draft-js.SelectionState)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>convertFromHTML (html)](#apidoc.element.draft-js.convertFromHTML)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>convertFromRaw (rawState)](#apidoc.element.draft-js.convertFromRaw)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>convertToRaw (contentState)](#apidoc.element.draft-js.convertToRaw)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>genKey ()](#apidoc.element.draft-js.genKey)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>getDefaultKeyBinding (e)](#apidoc.element.draft-js.getDefaultKeyBinding)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>getVisibleSelectionRect (global)](#apidoc.element.draft-js.getVisibleSelectionRect)
1.  object <span class="apidocSignatureSpan">draft-js.</span>AtomicBlockUtils
1.  object <span class="apidocSignatureSpan">draft-js.</span>BlockMapBuilder
1.  object <span class="apidocSignatureSpan">draft-js.</span>BlockTree
1.  object <span class="apidocSignatureSpan">draft-js.</span>CharacterMetadata.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>CompositeDecorator.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>ContentBlock.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>ContentState.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>ContentStateInlineStyle
1.  object <span class="apidocSignatureSpan">draft-js.</span>DefaultDraftBlockRenderMap
1.  object <span class="apidocSignatureSpan">draft-js.</span>DefaultDraftInlineStyle
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEditorCompositionHandler
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEditorContents_react.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEditorDragHandler
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEditorEditHandler
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEditorLeaf_react.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEditorPlaceholder_react.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEditorTextNode_react.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftEntitySegments
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftOffsetKey
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftPasteProcessor
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftRemovableWord
1.  object <span class="apidocSignatureSpan">draft-js.</span>DraftStringKey
1.  object <span class="apidocSignatureSpan">draft-js.</span>Editor.defaultProps
1.  object <span class="apidocSignatureSpan">draft-js.</span>Editor.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>EditorBidiService
1.  object <span class="apidocSignatureSpan">draft-js.</span>EditorBlock.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>EditorState.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>Entity
1.  object <span class="apidocSignatureSpan">draft-js.</span>EntityInstance.prototype
1.  object <span class="apidocSignatureSpan">draft-js.</span>KeyBindingUtil
1.  object <span class="apidocSignatureSpan">draft-js.</span>Modifier
1.  object <span class="apidocSignatureSpan">draft-js.</span>RichUtils
1.  object <span class="apidocSignatureSpan">draft-js.</span>SecondaryClipboard
1.  object <span class="apidocSignatureSpan">draft-js.</span>SelectionState.prototype

#### [module draft-js.AtomicBlockUtils](#apidoc.module.draft-js.AtomicBlockUtils)
1.  [function <span class="apidocSignatureSpan">draft-js.AtomicBlockUtils.</span>insertAtomicBlock (editorState, entityKey, character)](#apidoc.element.draft-js.AtomicBlockUtils.insertAtomicBlock)

#### [module draft-js.BlockMapBuilder](#apidoc.module.draft-js.BlockMapBuilder)
1.  [function <span class="apidocSignatureSpan">draft-js.BlockMapBuilder.</span>createFromArray (blocks)](#apidoc.element.draft-js.BlockMapBuilder.createFromArray)

#### [module draft-js.BlockTree](#apidoc.module.draft-js.BlockTree)
1.  [function <span class="apidocSignatureSpan">draft-js.BlockTree.</span>generate (contentState, block, decorator)](#apidoc.element.draft-js.BlockTree.generate)
1.  [function <span class="apidocSignatureSpan">draft-js.BlockTree.</span>getFingerprint (tree)](#apidoc.element.draft-js.BlockTree.getFingerprint)

#### [module draft-js.CharacterMetadata](#apidoc.module.draft-js.CharacterMetadata)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>CharacterMetadata ()](#apidoc.element.draft-js.CharacterMetadata.CharacterMetadata)
1.  [function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>applyEntity (record, entityKey)](#apidoc.element.draft-js.CharacterMetadata.applyEntity)
1.  [function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>applyStyle (record, style)](#apidoc.element.draft-js.CharacterMetadata.applyStyle)
1.  [function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>create (config)](#apidoc.element.draft-js.CharacterMetadata.create)
1.  [function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>removeStyle (record, style)](#apidoc.element.draft-js.CharacterMetadata.removeStyle)
1.  object <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>EMPTY

#### [module draft-js.CharacterMetadata.prototype](#apidoc.module.draft-js.CharacterMetadata.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.prototype.</span>getEntity ()](#apidoc.element.draft-js.CharacterMetadata.prototype.getEntity)
1.  [function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.prototype.</span>getStyle ()](#apidoc.element.draft-js.CharacterMetadata.prototype.getStyle)
1.  [function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.prototype.</span>hasStyle (style)](#apidoc.element.draft-js.CharacterMetadata.prototype.hasStyle)

#### [module draft-js.CompositeDecorator](#apidoc.module.draft-js.CompositeDecorator)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>CompositeDecorator (decorators)](#apidoc.element.draft-js.CompositeDecorator.CompositeDecorator)

#### [module draft-js.CompositeDecorator.prototype](#apidoc.module.draft-js.CompositeDecorator.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.CompositeDecorator.prototype.</span>getComponentForKey (key)](#apidoc.element.draft-js.CompositeDecorator.prototype.getComponentForKey)
1.  [function <span class="apidocSignatureSpan">draft-js.CompositeDecorator.prototype.</span>getDecorations (block, contentState)](#apidoc.element.draft-js.CompositeDecorator.prototype.getDecorations)
1.  [function <span class="apidocSignatureSpan">draft-js.CompositeDecorator.prototype.</span>getPropsForKey (key)](#apidoc.element.draft-js.CompositeDecorator.prototype.getPropsForKey)

#### [module draft-js.ContentBlock](#apidoc.module.draft-js.ContentBlock)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>ContentBlock ()](#apidoc.element.draft-js.ContentBlock.ContentBlock)

#### [module draft-js.ContentBlock.prototype](#apidoc.module.draft-js.ContentBlock.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>findEntityRanges (filterFn, callback)](#apidoc.element.draft-js.ContentBlock.prototype.findEntityRanges)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>findStyleRanges (filterFn, callback)](#apidoc.element.draft-js.ContentBlock.prototype.findStyleRanges)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getCharacterList ()](#apidoc.element.draft-js.ContentBlock.prototype.getCharacterList)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getData ()](#apidoc.element.draft-js.ContentBlock.prototype.getData)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getDepth ()](#apidoc.element.draft-js.ContentBlock.prototype.getDepth)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getEntityAt (offset)](#apidoc.element.draft-js.ContentBlock.prototype.getEntityAt)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getInlineStyleAt (offset)](#apidoc.element.draft-js.ContentBlock.prototype.getInlineStyleAt)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getKey ()](#apidoc.element.draft-js.ContentBlock.prototype.getKey)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getLength ()](#apidoc.element.draft-js.ContentBlock.prototype.getLength)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getText ()](#apidoc.element.draft-js.ContentBlock.prototype.getText)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getType ()](#apidoc.element.draft-js.ContentBlock.prototype.getType)

#### [module draft-js.ContentState](#apidoc.module.draft-js.ContentState)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>ContentState ()](#apidoc.element.draft-js.ContentState.ContentState)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.</span>createFromBlockArray ( // TODO: update flow type when we completely deprecate the old entity API blocks, entityMap)](#apidoc.element.draft-js.ContentState.createFromBlockArray)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.</span>createFromText (text)](#apidoc.element.draft-js.ContentState.createFromText)

#### [module draft-js.ContentState.prototype](#apidoc.module.draft-js.ContentState.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>addEntity (instance)](#apidoc.element.draft-js.ContentState.prototype.addEntity)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>createEntity (type, mutability, data)](#apidoc.element.draft-js.ContentState.prototype.createEntity)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockAfter (key)](#apidoc.element.draft-js.ContentState.prototype.getBlockAfter)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockBefore (key)](#apidoc.element.draft-js.ContentState.prototype.getBlockBefore)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockForKey (key)](#apidoc.element.draft-js.ContentState.prototype.getBlockForKey)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockMap ()](#apidoc.element.draft-js.ContentState.prototype.getBlockMap)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlocksAsArray ()](#apidoc.element.draft-js.ContentState.prototype.getBlocksAsArray)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getEntity (key)](#apidoc.element.draft-js.ContentState.prototype.getEntity)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getEntityMap ()](#apidoc.element.draft-js.ContentState.prototype.getEntityMap)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getFirstBlock ()](#apidoc.element.draft-js.ContentState.prototype.getFirstBlock)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getKeyAfter (key)](#apidoc.element.draft-js.ContentState.prototype.getKeyAfter)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getKeyBefore (key)](#apidoc.element.draft-js.ContentState.prototype.getKeyBefore)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getLastBlock ()](#apidoc.element.draft-js.ContentState.prototype.getLastBlock)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getLastCreatedEntityKey ()](#apidoc.element.draft-js.ContentState.prototype.getLastCreatedEntityKey)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getPlainText (delimiter)](#apidoc.element.draft-js.ContentState.prototype.getPlainText)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getSelectionAfter ()](#apidoc.element.draft-js.ContentState.prototype.getSelectionAfter)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getSelectionBefore ()](#apidoc.element.draft-js.ContentState.prototype.getSelectionBefore)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>hasText ()](#apidoc.element.draft-js.ContentState.prototype.hasText)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>mergeEntityData (key, toMerge)](#apidoc.element.draft-js.ContentState.prototype.mergeEntityData)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>replaceEntityData (key, newData)](#apidoc.element.draft-js.ContentState.prototype.replaceEntityData)

#### [module draft-js.ContentStateInlineStyle](#apidoc.module.draft-js.ContentStateInlineStyle)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentStateInlineStyle.</span>add (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.ContentStateInlineStyle.add)
1.  [function <span class="apidocSignatureSpan">draft-js.ContentStateInlineStyle.</span>remove (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.ContentStateInlineStyle.remove)

#### [module draft-js.DraftEditorCompositionHandler](#apidoc.module.draft-js.DraftEditorCompositionHandler)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onBeforeInput (editor, e)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onBeforeInput)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onCompositionEnd (editor)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onCompositionEnd)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onCompositionStart (editor)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onCompositionStart)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onKeyDown (editor, e)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onKeyDown)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onKeyPress (editor, e)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onKeyPress)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>resolveComposition (editor)](#apidoc.element.draft-js.DraftEditorCompositionHandler.resolveComposition)

#### [module draft-js.DraftEditorContents_react](#apidoc.module.draft-js.DraftEditorContents_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorContents_react ()](#apidoc.element.draft-js.DraftEditorContents_react.DraftEditorContents_react)

#### [module draft-js.DraftEditorContents_react.prototype](#apidoc.module.draft-js.DraftEditorContents_react.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorContents_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorContents_react.prototype.render)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorContents_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorContents_react.prototype.shouldComponentUpdate)

#### [module draft-js.DraftEditorDragHandler](#apidoc.module.draft-js.DraftEditorDragHandler)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorDragHandler.</span>onDragEnd (editor)](#apidoc.element.draft-js.DraftEditorDragHandler.onDragEnd)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorDragHandler.</span>onDrop (editor, e)](#apidoc.element.draft-js.DraftEditorDragHandler.onDrop)

#### [module draft-js.DraftEditorEditHandler](#apidoc.module.draft-js.DraftEditorEditHandler)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onBeforeInput (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onBeforeInput)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onBlur (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onBlur)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onCompositionStart (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onCompositionStart)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onCopy (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onCopy)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onCut (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onCut)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onDragOver (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onDragOver)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onDragStart (editor)](#apidoc.element.draft-js.DraftEditorEditHandler.onDragStart)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onFocus (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onFocus)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onInput (editor)](#apidoc.element.draft-js.DraftEditorEditHandler.onInput)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onKeyDown (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onKeyDown)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onPaste (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onPaste)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onSelect (editor)](#apidoc.element.draft-js.DraftEditorEditHandler.onSelect)

#### [module draft-js.DraftEditorLeaf_react](#apidoc.module.draft-js.DraftEditorLeaf_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorLeaf_react ()](#apidoc.element.draft-js.DraftEditorLeaf_react.DraftEditorLeaf_react)

#### [module draft-js.DraftEditorLeaf_react.prototype](#apidoc.module.draft-js.DraftEditorLeaf_react.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>_setSelection ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype._setSelection)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>componentDidMount ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>componentDidUpdate ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.render)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.shouldComponentUpdate)

#### [module draft-js.DraftEditorPlaceholder_react](#apidoc.module.draft-js.DraftEditorPlaceholder_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorPlaceholder_react ()](#apidoc.element.draft-js.DraftEditorPlaceholder_react.DraftEditorPlaceholder_react)

#### [module draft-js.DraftEditorPlaceholder_react.prototype](#apidoc.module.draft-js.DraftEditorPlaceholder_react.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorPlaceholder_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorPlaceholder_react.prototype.render)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorPlaceholder_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorPlaceholder_react.prototype.shouldComponentUpdate)

#### [module draft-js.DraftEditorTextNode_react](#apidoc.module.draft-js.DraftEditorTextNode_react)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorTextNode_react (props)](#apidoc.element.draft-js.DraftEditorTextNode_react.DraftEditorTextNode_react)

#### [module draft-js.DraftEditorTextNode_react.prototype](#apidoc.module.draft-js.DraftEditorTextNode_react.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorTextNode_react.prototype.</span>componentWillUpdate ()](#apidoc.element.draft-js.DraftEditorTextNode_react.prototype.componentWillUpdate)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorTextNode_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorTextNode_react.prototype.render)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEditorTextNode_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorTextNode_react.prototype.shouldComponentUpdate)

#### [module draft-js.DraftEntitySegments](#apidoc.module.draft-js.DraftEntitySegments)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftEntitySegments.</span>getRemovalRange (selectionStart, selectionEnd, text, entityStart, direction)](#apidoc.element.draft-js.DraftEntitySegments.getRemovalRange)

#### [module draft-js.DraftOffsetKey](#apidoc.module.draft-js.DraftOffsetKey)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftOffsetKey.</span>decode (offsetKey)](#apidoc.element.draft-js.DraftOffsetKey.decode)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftOffsetKey.</span>encode (blockKey, decoratorKey, leafKey)](#apidoc.element.draft-js.DraftOffsetKey.encode)

#### [module draft-js.DraftPasteProcessor](#apidoc.module.draft-js.DraftPasteProcessor)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftPasteProcessor.</span>processHTML (html, blockRenderMap)](#apidoc.element.draft-js.DraftPasteProcessor.processHTML)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftPasteProcessor.</span>processText (textBlocks, character)](#apidoc.element.draft-js.DraftPasteProcessor.processText)

#### [module draft-js.DraftRemovableWord](#apidoc.module.draft-js.DraftRemovableWord)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftRemovableWord.</span>getBackward (text)](#apidoc.element.draft-js.DraftRemovableWord.getBackward)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftRemovableWord.</span>getForward (text)](#apidoc.element.draft-js.DraftRemovableWord.getForward)

#### [module draft-js.DraftStringKey](#apidoc.module.draft-js.DraftStringKey)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftStringKey.</span>stringify (key)](#apidoc.element.draft-js.DraftStringKey.stringify)
1.  [function <span class="apidocSignatureSpan">draft-js.DraftStringKey.</span>unstringify (key)](#apidoc.element.draft-js.DraftStringKey.unstringify)

#### [module draft-js.Editor](#apidoc.module.draft-js.Editor)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>Editor (props)](#apidoc.element.draft-js.Editor.Editor)
1.  object <span class="apidocSignatureSpan">draft-js.Editor.</span>defaultProps

#### [module draft-js.Editor.defaultProps](#apidoc.module.draft-js.Editor.defaultProps)
1.  boolean <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>readOnly
1.  boolean <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>spellCheck
1.  boolean <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>stripPastedStyles
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>blockRendererFn ()](#apidoc.element.draft-js.Editor.defaultProps.blockRendererFn)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>blockStyleFn ()](#apidoc.element.draft-js.Editor.defaultProps.blockStyleFn)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>keyBindingFn (e)](#apidoc.element.draft-js.Editor.defaultProps.keyBindingFn)
1.  object <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>blockRenderMap

#### [module draft-js.Editor.prototype](#apidoc.module.draft-js.Editor.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_blur ()](#apidoc.element.draft-js.Editor.prototype._blur)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_buildHandler (eventName)](#apidoc.element.draft-js.Editor.prototype._buildHandler)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_exitCurrentMode ()](#apidoc.element.draft-js.Editor.prototype._exitCurrentMode)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_focus (scrollPosition)](#apidoc.element.draft-js.Editor.prototype._focus)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_getClipboard ()](#apidoc.element.draft-js.Editor.prototype._getClipboard)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_onDragEnter ()](#apidoc.element.draft-js.Editor.prototype._onDragEnter)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_onDragLeave ()](#apidoc.element.draft-js.Editor.prototype._onDragLeave)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_renderPlaceholder ()](#apidoc.element.draft-js.Editor.prototype._renderPlaceholder)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_restoreEditorDOM (scrollPosition)](#apidoc.element.draft-js.Editor.prototype._restoreEditorDOM)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_setClipboard (clipboard)](#apidoc.element.draft-js.Editor.prototype._setClipboard)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_setMode (mode)](#apidoc.element.draft-js.Editor.prototype._setMode)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_showPlaceholder ()](#apidoc.element.draft-js.Editor.prototype._showPlaceholder)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_update (editorState)](#apidoc.element.draft-js.Editor.prototype._update)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>componentDidMount ()](#apidoc.element.draft-js.Editor.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>componentDidUpdate ()](#apidoc.element.draft-js.Editor.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>componentWillUpdate (nextProps)](#apidoc.element.draft-js.Editor.prototype.componentWillUpdate)
1.  [function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>render ()](#apidoc.element.draft-js.Editor.prototype.render)

#### [module draft-js.EditorBidiService](#apidoc.module.draft-js.EditorBidiService)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorBidiService.</span>getDirectionMap (content, prevBidiMap)](#apidoc.element.draft-js.EditorBidiService.getDirectionMap)

#### [module draft-js.EditorBlock](#apidoc.module.draft-js.EditorBlock)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>EditorBlock ()](#apidoc.element.draft-js.EditorBlock.EditorBlock)

#### [module draft-js.EditorBlock.prototype](#apidoc.module.draft-js.EditorBlock.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>_renderChildren ()](#apidoc.element.draft-js.EditorBlock.prototype._renderChildren)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>componentDidMount ()](#apidoc.element.draft-js.EditorBlock.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>render ()](#apidoc.element.draft-js.EditorBlock.prototype.render)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.EditorBlock.prototype.shouldComponentUpdate)

#### [module draft-js.EditorState](#apidoc.module.draft-js.EditorState)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>EditorState (immutable)](#apidoc.element.draft-js.EditorState.EditorState)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>acceptSelection (editorState, selection)](#apidoc.element.draft-js.EditorState.acceptSelection)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>create (config)](#apidoc.element.draft-js.EditorState.create)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>createEmpty (decorator)](#apidoc.element.draft-js.EditorState.createEmpty)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>createWithContent (contentState, decorator)](#apidoc.element.draft-js.EditorState.createWithContent)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>forceSelection (editorState, selection)](#apidoc.element.draft-js.EditorState.forceSelection)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>moveFocusToEnd (editorState)](#apidoc.element.draft-js.EditorState.moveFocusToEnd)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>moveSelectionToEnd (editorState)](#apidoc.element.draft-js.EditorState.moveSelectionToEnd)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>push (editorState, contentState, changeType)](#apidoc.element.draft-js.EditorState.push)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>redo (editorState)](#apidoc.element.draft-js.EditorState.redo)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>set (editorState, put)](#apidoc.element.draft-js.EditorState.set)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>setInlineStyleOverride (editorState, inlineStyleOverride)](#apidoc.element.draft-js.EditorState.setInlineStyleOverride)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.</span>undo (editorState)](#apidoc.element.draft-js.EditorState.undo)

#### [module draft-js.EditorState.prototype](#apidoc.module.draft-js.EditorState.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getAllowUndo ()](#apidoc.element.draft-js.EditorState.prototype.getAllowUndo)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getBlockTree (blockKey)](#apidoc.element.draft-js.EditorState.prototype.getBlockTree)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getCurrentContent ()](#apidoc.element.draft-js.EditorState.prototype.getCurrentContent)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getCurrentInlineStyle ()](#apidoc.element.draft-js.EditorState.prototype.getCurrentInlineStyle)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getDecorator ()](#apidoc.element.draft-js.EditorState.prototype.getDecorator)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getDirectionMap ()](#apidoc.element.draft-js.EditorState.prototype.getDirectionMap)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getImmutable ()](#apidoc.element.draft-js.EditorState.prototype.getImmutable)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getInlineStyleOverride ()](#apidoc.element.draft-js.EditorState.prototype.getInlineStyleOverride)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getLastChangeType ()](#apidoc.element.draft-js.EditorState.prototype.getLastChangeType)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getNativelyRenderedContent ()](#apidoc.element.draft-js.EditorState.prototype.getNativelyRenderedContent)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getRedoStack ()](#apidoc.element.draft-js.EditorState.prototype.getRedoStack)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getSelection ()](#apidoc.element.draft-js.EditorState.prototype.getSelection)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getUndoStack ()](#apidoc.element.draft-js.EditorState.prototype.getUndoStack)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>isInCompositionMode ()](#apidoc.element.draft-js.EditorState.prototype.isInCompositionMode)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>isSelectionAtEndOfContent ()](#apidoc.element.draft-js.EditorState.prototype.isSelectionAtEndOfContent)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>isSelectionAtStartOfContent ()](#apidoc.element.draft-js.EditorState.prototype.isSelectionAtStartOfContent)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>mustForceSelection ()](#apidoc.element.draft-js.EditorState.prototype.mustForceSelection)
1.  [function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>toJS ()](#apidoc.element.draft-js.EditorState.prototype.toJS)

#### [module draft-js.Entity](#apidoc.module.draft-js.Entity)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>__add (instance)](#apidoc.element.draft-js.Entity.__add)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>__create (type, mutability, data)](#apidoc.element.draft-js.Entity.__create)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>__get (key)](#apidoc.element.draft-js.Entity.__get)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>__getLastCreatedEntityKey ()](#apidoc.element.draft-js.Entity.__getLastCreatedEntityKey)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>__mergeData (key, toMerge)](#apidoc.element.draft-js.Entity.__mergeData)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>__replaceData (key, newData)](#apidoc.element.draft-js.Entity.__replaceData)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>add (instance)](#apidoc.element.draft-js.Entity.add)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>create (type, mutability, data)](#apidoc.element.draft-js.Entity.create)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>get (key)](#apidoc.element.draft-js.Entity.get)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>getLastCreatedEntityKey ()](#apidoc.element.draft-js.Entity.getLastCreatedEntityKey)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>mergeData (key, toMerge)](#apidoc.element.draft-js.Entity.mergeData)
1.  [function <span class="apidocSignatureSpan">draft-js.Entity.</span>replaceData (key, newData)](#apidoc.element.draft-js.Entity.replaceData)

#### [module draft-js.EntityInstance](#apidoc.module.draft-js.EntityInstance)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>EntityInstance ()](#apidoc.element.draft-js.EntityInstance.EntityInstance)

#### [module draft-js.EntityInstance.prototype](#apidoc.module.draft-js.EntityInstance.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.EntityInstance.prototype.</span>getData ()](#apidoc.element.draft-js.EntityInstance.prototype.getData)
1.  [function <span class="apidocSignatureSpan">draft-js.EntityInstance.prototype.</span>getMutability ()](#apidoc.element.draft-js.EntityInstance.prototype.getMutability)
1.  [function <span class="apidocSignatureSpan">draft-js.EntityInstance.prototype.</span>getType ()](#apidoc.element.draft-js.EntityInstance.prototype.getType)

#### [module draft-js.KeyBindingUtil](#apidoc.module.draft-js.KeyBindingUtil)
1.  [function <span class="apidocSignatureSpan">draft-js.KeyBindingUtil.</span>hasCommandModifier (e)](#apidoc.element.draft-js.KeyBindingUtil.hasCommandModifier)
1.  [function <span class="apidocSignatureSpan">draft-js.KeyBindingUtil.</span>isCtrlKeyCommand (e)](#apidoc.element.draft-js.KeyBindingUtil.isCtrlKeyCommand)
1.  [function <span class="apidocSignatureSpan">draft-js.KeyBindingUtil.</span>isOptionKeyCommand (e)](#apidoc.element.draft-js.KeyBindingUtil.isOptionKeyCommand)

#### [module draft-js.Modifier](#apidoc.module.draft-js.Modifier)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>applyEntity (contentState, selectionState, entityKey)](#apidoc.element.draft-js.Modifier.applyEntity)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>applyInlineStyle (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.Modifier.applyInlineStyle)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>insertText (contentState, targetRange, text, inlineStyle, entityKey)](#apidoc.element.draft-js.Modifier.insertText)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>mergeBlockData (contentState, selectionState, blockData)](#apidoc.element.draft-js.Modifier.mergeBlockData)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>moveText (contentState, removalRange, targetRange)](#apidoc.element.draft-js.Modifier.moveText)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>removeInlineStyle (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.Modifier.removeInlineStyle)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>removeRange (contentState, rangeToRemove, removalDirection)](#apidoc.element.draft-js.Modifier.removeRange)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>replaceText (contentState, rangeToReplace, text, inlineStyle, entityKey)](#apidoc.element.draft-js.Modifier.replaceText)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>replaceWithFragment (contentState, targetRange, fragment)](#apidoc.element.draft-js.Modifier.replaceWithFragment)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>setBlockData (contentState, selectionState, blockData)](#apidoc.element.draft-js.Modifier.setBlockData)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>setBlockType (contentState, selectionState, blockType)](#apidoc.element.draft-js.Modifier.setBlockType)
1.  [function <span class="apidocSignatureSpan">draft-js.Modifier.</span>splitBlock (contentState, selectionState)](#apidoc.element.draft-js.Modifier.splitBlock)

#### [module draft-js.RichUtils](#apidoc.module.draft-js.RichUtils)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>currentBlockContainsLink (editorState)](#apidoc.element.draft-js.RichUtils.currentBlockContainsLink)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>getCurrentBlockType (editorState)](#apidoc.element.draft-js.RichUtils.getCurrentBlockType)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>getDataObjectForLinkURL (uri)](#apidoc.element.draft-js.RichUtils.getDataObjectForLinkURL)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>handleKeyCommand (editorState, command)](#apidoc.element.draft-js.RichUtils.handleKeyCommand)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>insertSoftNewline (editorState)](#apidoc.element.draft-js.RichUtils.insertSoftNewline)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>onBackspace (editorState)](#apidoc.element.draft-js.RichUtils.onBackspace)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>onDelete (editorState)](#apidoc.element.draft-js.RichUtils.onDelete)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>onTab (event, editorState, maxDepth)](#apidoc.element.draft-js.RichUtils.onTab)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleBlockType (editorState, blockType)](#apidoc.element.draft-js.RichUtils.toggleBlockType)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleCode (editorState)](#apidoc.element.draft-js.RichUtils.toggleCode)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleInlineStyle (editorState, inlineStyle)](#apidoc.element.draft-js.RichUtils.toggleInlineStyle)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleLink (editorState, targetSelection, entityKey)](#apidoc.element.draft-js.RichUtils.toggleLink)
1.  [function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>tryToRemoveBlockStyle (editorState)](#apidoc.element.draft-js.RichUtils.tryToRemoveBlockStyle)

#### [module draft-js.SecondaryClipboard](#apidoc.module.draft-js.SecondaryClipboard)
1.  [function <span class="apidocSignatureSpan">draft-js.SecondaryClipboard.</span>cut (editorState)](#apidoc.element.draft-js.SecondaryClipboard.cut)
1.  [function <span class="apidocSignatureSpan">draft-js.SecondaryClipboard.</span>paste (editorState)](#apidoc.element.draft-js.SecondaryClipboard.paste)

#### [module draft-js.SelectionState](#apidoc.module.draft-js.SelectionState)
1.  [function <span class="apidocSignatureSpan">draft-js.</span>SelectionState ()](#apidoc.element.draft-js.SelectionState.SelectionState)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.</span>createEmpty (key)](#apidoc.element.draft-js.SelectionState.createEmpty)

#### [module draft-js.SelectionState.prototype](#apidoc.module.draft-js.SelectionState.prototype)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getAnchorKey ()](#apidoc.element.draft-js.SelectionState.prototype.getAnchorKey)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getAnchorOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getAnchorOffset)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getEndKey ()](#apidoc.element.draft-js.SelectionState.prototype.getEndKey)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getEndOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getEndOffset)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getFocusKey ()](#apidoc.element.draft-js.SelectionState.prototype.getFocusKey)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getFocusOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getFocusOffset)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getHasFocus ()](#apidoc.element.draft-js.SelectionState.prototype.getHasFocus)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getIsBackward ()](#apidoc.element.draft-js.SelectionState.prototype.getIsBackward)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getStartKey ()](#apidoc.element.draft-js.SelectionState.prototype.getStartKey)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getStartOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getStartOffset)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>hasEdgeWithin (blockKey, start, end)](#apidoc.element.draft-js.SelectionState.prototype.hasEdgeWithin)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>isCollapsed ()](#apidoc.element.draft-js.SelectionState.prototype.isCollapsed)
1.  [function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>serialize ()](#apidoc.element.draft-js.SelectionState.prototype.serialize)



# <a name="apidoc.module.draft-js"></a>[module draft-js](#apidoc.module.draft-js)

#### <a name="apidoc.element.draft-js.CharacterMetadata"></a>[function <span class="apidocSignatureSpan">draft-js.</span>CharacterMetadata ()](#apidoc.element.draft-js.CharacterMetadata)
- description and source-code
```javascript
function CharacterMetadata() {
  _classCallCheck(this, CharacterMetadata);

  return _possibleConstructorReturn(this, _CharacterMetadataRec.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.CompositeDecorator"></a>[function <span class="apidocSignatureSpan">draft-js.</span>CompositeDecorator (decorators)](#apidoc.element.draft-js.CompositeDecorator)
- description and source-code
```javascript
function CompositeDraftDecorator(decorators) {
  _classCallCheck(this, CompositeDraftDecorator);

  // Copy the decorator array, since we use this array order to determine
  // precedence of decoration matching. If the array is mutated externally,
  // we don't want to be affected here.
  this._decorators = decorators.slice();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentBlock"></a>[function <span class="apidocSignatureSpan">draft-js.</span>ContentBlock ()](#apidoc.element.draft-js.ContentBlock)
- description and source-code
```javascript
function ContentBlock() {
  _classCallCheck(this, ContentBlock);

  return _possibleConstructorReturn(this, _ContentBlockRecord.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState"></a>[function <span class="apidocSignatureSpan">draft-js.</span>ContentState ()](#apidoc.element.draft-js.ContentState)
- description and source-code
```javascript
function ContentState() {
  _classCallCheck(this, ContentState);

  return _possibleConstructorReturn(this, _ContentStateRecord.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorContents_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorContents_react ()](#apidoc.element.draft-js.DraftEditorContents_react)
- description and source-code
```javascript
function DraftEditorContents() {
  _classCallCheck(this, DraftEditorContents);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorLeaf_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorLeaf_react ()](#apidoc.element.draft-js.DraftEditorLeaf_react)
- description and source-code
```javascript
function DraftEditorLeaf() {
  _classCallCheck(this, DraftEditorLeaf);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorPlaceholder_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorPlaceholder_react ()](#apidoc.element.draft-js.DraftEditorPlaceholder_react)
- description and source-code
```javascript
function DraftEditorPlaceholder() {
  _classCallCheck(this, DraftEditorPlaceholder);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorTextNode_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorTextNode_react (props)](#apidoc.element.draft-js.DraftEditorTextNode_react)
- description and source-code
```javascript
function DraftEditorTextNode(props) {
  _classCallCheck(this, DraftEditorTextNode);

  var _this = _possibleConstructorReturn(this, _React$Component.call(this, props));

  _this._forceFlag = false;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor"></a>[function <span class="apidocSignatureSpan">draft-js.</span>Editor (props)](#apidoc.element.draft-js.Editor)
- description and source-code
```javascript
function DraftEditor(props) {
  _classCallCheck(this, DraftEditor);

  var _this = _possibleConstructorReturn(this, _React$Component.call(this, props));

  _this._blockSelectEvents = false;
  _this._clipboard = null;
  _this._handler = null;
  _this._dragCount = 0;
  _this._editorKey = generateRandomKey();
  _this._placeholderAccessibilityID = 'placeholder-' + _this._editorKey;
  _this._latestEditorState = props.editorState;

  _this._onBeforeInput = _this._buildHandler('onBeforeInput');
  _this._onBlur = _this._buildHandler('onBlur');
  _this._onCharacterData = _this._buildHandler('onCharacterData');
  _this._onCompositionEnd = _this._buildHandler('onCompositionEnd');
  _this._onCompositionStart = _this._buildHandler('onCompositionStart');
  _this._onCopy = _this._buildHandler('onCopy');
  _this._onCut = _this._buildHandler('onCut');
  _this._onDragEnd = _this._buildHandler('onDragEnd');
  _this._onDragOver = _this._buildHandler('onDragOver');
  _this._onDragStart = _this._buildHandler('onDragStart');
  _this._onDrop = _this._buildHandler('onDrop');
  _this._onInput = _this._buildHandler('onInput');
  _this._onFocus = _this._buildHandler('onFocus');
  _this._onKeyDown = _this._buildHandler('onKeyDown');
  _this._onKeyPress = _this._buildHandler('onKeyPress');
  _this._onKeyUp = _this._buildHandler('onKeyUp');
  _this._onMouseDown = _this._buildHandler('onMouseDown');
  _this._onMouseUp = _this._buildHandler('onMouseUp');
  _this._onPaste = _this._buildHandler('onPaste');
  _this._onSelect = _this._buildHandler('onSelect');

  // Manual binding for public and internal methods.
  _this.focus = _this._focus.bind(_this);
  _this.blur = _this._blur.bind(_this);
  _this.setMode = _this._setMode.bind(_this);
  _this.exitCurrentMode = _this._exitCurrentMode.bind(_this);
  _this.restoreEditorDOM = _this._restoreEditorDOM.bind(_this);
  _this.setClipboard = _this._setClipboard.bind(_this);
  _this.getClipboard = _this._getClipboard.bind(_this);
  _this.getEditorKey = function () {
    return _this._editorKey;
  };
  _this.update = _this._update.bind(_this);
  _this.onDragEnter = _this._onDragEnter.bind(_this);
  _this.onDragLeave = _this._onDragLeave.bind(_this);

  // See '_restoreEditorDOM()'.
  _this.state = { containerKey: 0 };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorBlock"></a>[function <span class="apidocSignatureSpan">draft-js.</span>EditorBlock ()](#apidoc.element.draft-js.EditorBlock)
- description and source-code
```javascript
function DraftEditorBlock() {
  _classCallCheck(this, DraftEditorBlock);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState"></a>[function <span class="apidocSignatureSpan">draft-js.</span>EditorState (immutable)](#apidoc.element.draft-js.EditorState)
- description and source-code
```javascript
function EditorState(immutable) {
  _classCallCheck(this, EditorState);

  this._immutable = immutable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EntityInstance"></a>[function <span class="apidocSignatureSpan">draft-js.</span>EntityInstance ()](#apidoc.element.draft-js.EntityInstance)
- description and source-code
```javascript
function DraftEntityInstance() {
  _classCallCheck(this, DraftEntityInstance);

  return _possibleConstructorReturn(this, _DraftEntityInstanceR.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.SelectionState"></a>[function <span class="apidocSignatureSpan">draft-js.</span>SelectionState ()](#apidoc.element.draft-js.SelectionState)
- description and source-code
```javascript
function SelectionState() {
  _classCallCheck(this, SelectionState);

  return _possibleConstructorReturn(this, _SelectionStateRecord.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.convertFromHTML"></a>[function <span class="apidocSignatureSpan">draft-js.</span>convertFromHTML (html)](#apidoc.element.draft-js.convertFromHTML)
- description and source-code
```javascript
function convertFromHTMLtoContentBlocks(html) {
  var DOMBuilder = arguments.length <= 1 || arguments[1] === undefined ? getSafeBodyFromHTML : arguments[1];
  var blockRenderMap = arguments.length <= 2 || arguments[2] === undefined ? DefaultDraftBlockRenderMap : arguments[2];

  // Be ABSOLUTELY SURE that the dom builder you pass here won't execute
  // arbitrary code in whatever environment you're running this in. For an
  // example of how we try to do this in-browser, see getSafeBodyFromHTML.

  // TODO: replace DraftEntity with an OrderedMap here
  var chunkData = getChunkForHTML(html, DOMBuilder, blockRenderMap, DraftEntity);

  if (chunkData == null) {
    return null;
  }

  var chunk = chunkData.chunk;
  var newEntityMap = chunkData.entityMap;


  var start = 0;
  return {
    contentBlocks: chunk.text.split('\r').map(function (textBlock, ii) {
      // Make absolutely certain that our text is acceptable.
      textBlock = sanitizeDraftText(textBlock);
      var end = start + textBlock.length;
      var inlines = nullthrows(chunk).inlines.slice(start, end);
      var entities = nullthrows(chunk).entities.slice(start, end);
      var characterList = List(inlines.map(function (style, ii) {
        var data = { style: style, entity: null };
        if (entities[ii]) {
          data.entity = entities[ii];
        }
        return CharacterMetadata.create(data);
      }));
      start = end + 1;

      return new ContentBlock({
        key: generateRandomKey(),
        type: nullthrows(chunk).blocks[ii].type,
        depth: nullthrows(chunk).blocks[ii].depth,
        text: textBlock,
        characterList: characterList
      });
    }),
    entityMap: newEntityMap
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.convertFromRaw"></a>[function <span class="apidocSignatureSpan">draft-js.</span>convertFromRaw (rawState)](#apidoc.element.draft-js.convertFromRaw)
- description and source-code
```javascript
function convertFromRawToDraftState(rawState) {
  var blocks = rawState.blocks;
  var entityMap = rawState.entityMap;


  var fromStorageToLocal = {};

  // TODO: Update this once we completely remove DraftEntity
  Object.keys(entityMap).forEach(function (storageKey) {
    var encodedEntity = entityMap[storageKey];
    var type = encodedEntity.type;
    var mutability = encodedEntity.mutability;
    var data = encodedEntity.data;

    var newKey = DraftEntity.__create(type, mutability, data || {});
    fromStorageToLocal[storageKey] = newKey;
  });

  var contentBlocks = blocks.map(function (block) {
    var key = block.key;
    var type = block.type;
    var text = block.text;
    var depth = block.depth;
    var inlineStyleRanges = block.inlineStyleRanges;
    var entityRanges = block.entityRanges;
    var data = block.data;

    key = key || generateRandomKey();
    depth = depth || 0;
    inlineStyleRanges = inlineStyleRanges || [];
    entityRanges = entityRanges || [];
    data = Map(data);

    var inlineStyles = decodeInlineStyleRanges(text, inlineStyleRanges);

    // Translate entity range keys to the DraftEntity map.
    var filteredEntityRanges = entityRanges.filter(function (range) {
      return fromStorageToLocal.hasOwnProperty(range.key);
    }).map(function (range) {
      return _extends({}, range, { key: fromStorageToLocal[range.key] });
    });

    var entities = decodeEntityRanges(text, filteredEntityRanges);
    var characterList = createCharacterList(inlineStyles, entities);

    return new ContentBlock({ key: key, type: type, text: text, depth: depth, characterList: characterList, data: data });
  });

  return ContentState.createFromBlockArray(contentBlocks);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.convertToRaw"></a>[function <span class="apidocSignatureSpan">draft-js.</span>convertToRaw (contentState)](#apidoc.element.draft-js.convertToRaw)
- description and source-code
```javascript
function convertFromDraftStateToRaw(contentState) {
  var entityStorageKey = 0;
  var entityStorageMap = {};
  var rawBlocks = [];

  contentState.getBlockMap().forEach(function (block, blockKey) {
    block.findEntityRanges(function (character) {
      return character.getEntity() !== null;
    }, function (start) {
      // Stringify to maintain order of otherwise numeric keys.
      var stringifiedEntityKey = DraftStringKey.stringify(block.getEntityAt(start));
      if (!entityStorageMap.hasOwnProperty(stringifiedEntityKey)) {
        entityStorageMap[stringifiedEntityKey] = '' + entityStorageKey++;
      }
    });

    rawBlocks.push({
      key: blockKey,
      text: block.getText(),
      type: block.getType(),
      depth: block.getDepth(),
      inlineStyleRanges: encodeInlineStyleRanges(block),
      entityRanges: encodeEntityRanges(block, entityStorageMap),
      data: block.getData().toObject()
    });
  });

  // Flip storage map so that our storage keys map to global
  // DraftEntity keys.
  var entityKeys = Object.keys(entityStorageMap);
  var flippedStorageMap = {};
  entityKeys.forEach(function (key, jj) {
    var entity = contentState.getEntity(DraftStringKey.unstringify(key));
    flippedStorageMap[jj] = {
      type: entity.getType(),
      mutability: entity.getMutability(),
      data: entity.getData()
    };
  });

  return {
    entityMap: flippedStorageMap,
    blocks: rawBlocks
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.genKey"></a>[function <span class="apidocSignatureSpan">draft-js.</span>genKey ()](#apidoc.element.draft-js.genKey)
- description and source-code
```javascript
function generateRandomKey() {
  var key = void 0;
  while (key === undefined || seenKeys.hasOwnProperty(key) || !isNaN(+key)) {
    key = Math.floor(Math.random() * MULTIPLIER).toString(32);
  }
  seenKeys[key] = true;
  return key;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.getDefaultKeyBinding"></a>[function <span class="apidocSignatureSpan">draft-js.</span>getDefaultKeyBinding (e)](#apidoc.element.draft-js.getDefaultKeyBinding)
- description and source-code
```javascript
function getDefaultKeyBinding(e) {
  switch (e.keyCode) {
    case 66:
      // B
      return hasCommandModifier(e) ? 'bold' : null;
    case 68:
      // D
      return isCtrlKeyCommand(e) ? 'delete' : null;
    case 72:
      // H
      return isCtrlKeyCommand(e) ? 'backspace' : null;
    case 73:
      // I
      return hasCommandModifier(e) ? 'italic' : null;
    case 74:
      // J
      return hasCommandModifier(e) ? 'code' : null;
    case 75:
      // K
      return !isWindows && isCtrlKeyCommand(e) ? 'secondary-cut' : null;
    case 77:
      // M
      return isCtrlKeyCommand(e) ? 'split-block' : null;
    case 79:
      // O
      return isCtrlKeyCommand(e) ? 'split-block' : null;
    case 84:
      // T
      return isOSX && isCtrlKeyCommand(e) ? 'transpose-characters' : null;
    case 85:
      // U
      return hasCommandModifier(e) ? 'underline' : null;
    case 87:
      // W
      return isOSX && isCtrlKeyCommand(e) ? 'backspace-word' : null;
    case 89:
      // Y
      if (isCtrlKeyCommand(e)) {
        return isWindows ? 'redo' : 'secondary-paste';
      }
      return null;
    case 90:
      // Z
      return getZCommand(e) || null;
    case Keys.RETURN:
      return 'split-block';
    case Keys.DELETE:
      return getDeleteCommand(e);
    case Keys.BACKSPACE:
      return getBackspaceCommand(e);
    // LEFT/RIGHT handlers serve as a workaround for a Firefox bug.
    case Keys.LEFT:
      return shouldFixFirefoxMovement && hasCommandModifier(e) ? 'move-selection-to-start-of-block' : null;
    case Keys.RIGHT:
      return shouldFixFirefoxMovement && hasCommandModifier(e) ? 'move-selection-to-end-of-block' : null;
    default:
      return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.getVisibleSelectionRect"></a>[function <span class="apidocSignatureSpan">draft-js.</span>getVisibleSelectionRect (global)](#apidoc.element.draft-js.getVisibleSelectionRect)
- description and source-code
```javascript
function getVisibleSelectionRect(global) {
  var selection = global.getSelection();
  if (!selection.rangeCount) {
    return null;
  }

  var range = selection.getRangeAt(0);
  var boundingRect = getRangeBoundingClientRect(range);
  var top = boundingRect.top;
  var right = boundingRect.right;
  var bottom = boundingRect.bottom;
  var left = boundingRect.left;

  // When a re-render leads to a node being removed, the DOM selection will
  // temporarily be placed on an ancestor node, which leads to an invalid
  // bounding rect. Discard this state.

  if (top === 0 && right === 0 && bottom === 0 && left === 0) {
    return null;
  }

  return boundingRect;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.AtomicBlockUtils"></a>[module draft-js.AtomicBlockUtils](#apidoc.module.draft-js.AtomicBlockUtils)

#### <a name="apidoc.element.draft-js.AtomicBlockUtils.insertAtomicBlock"></a>[function <span class="apidocSignatureSpan">draft-js.AtomicBlockUtils.</span>insertAtomicBlock (editorState, entityKey, character)](#apidoc.element.draft-js.AtomicBlockUtils.insertAtomicBlock)
- description and source-code
```javascript
function insertAtomicBlock(editorState, entityKey, character) {
  var contentState = editorState.getCurrentContent();
  var selectionState = editorState.getSelection();

  var afterRemoval = DraftModifier.removeRange(contentState, selectionState, 'backward');

  var targetSelection = afterRemoval.getSelectionAfter();
  var afterSplit = DraftModifier.splitBlock(afterRemoval, targetSelection);
  var insertionTarget = afterSplit.getSelectionAfter();

  var asAtomicBlock = DraftModifier.setBlockType(afterSplit, insertionTarget, 'atomic');

  var charData = CharacterMetadata.create({ entity: entityKey });

  var fragmentArray = [new ContentBlock({
    key: generateRandomKey(),
    type: 'atomic',
    text: character,
    characterList: List(Repeat(charData, character.length))
  }), new ContentBlock({
    key: generateRandomKey(),
    type: 'unstyled',
    text: '',
    characterList: List()
  })];

  var fragment = BlockMapBuilder.createFromArray(fragmentArray);

  var withAtomicBlock = DraftModifier.replaceWithFragment(asAtomicBlock, insertionTarget, fragment);

  var newContent = withAtomicBlock.merge({
    selectionBefore: selectionState,
    selectionAfter: withAtomicBlock.getSelectionAfter().set('hasFocus', true)
  });

  return EditorState.push(editorState, newContent, 'insert-fragment');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.BlockMapBuilder"></a>[module draft-js.BlockMapBuilder](#apidoc.module.draft-js.BlockMapBuilder)

#### <a name="apidoc.element.draft-js.BlockMapBuilder.createFromArray"></a>[function <span class="apidocSignatureSpan">draft-js.BlockMapBuilder.</span>createFromArray (blocks)](#apidoc.element.draft-js.BlockMapBuilder.createFromArray)
- description and source-code
```javascript
function createFromArray(blocks) {
  return OrderedMap(blocks.map(function (block) {
    return [block.getKey(), block];
  }));
}
```
- example usage
```shell
...
  var blocks = splitTextIntoTextBlocks(fileText);
  var character = CharacterMetadata.create({
    style: editorState.getCurrentInlineStyle(),
    entity: getEntityKeyForSelection(editorState.getCurrentContent(), editorState.getSelection())
  });

  var text = DraftPasteProcessor.processText(blocks, character);
  var fragment = BlockMapBuilder.createFromArray(text);

  var withInsertedText = DraftModifier.replaceWithFragment(editorState.getCurrentContent(), editorState.getSelection(), fragment
);

  editor.update(EditorState.push(editorState, withInsertedText, 'insert-fragment'));
});

return;
...
```



# <a name="apidoc.module.draft-js.BlockTree"></a>[module draft-js.BlockTree](#apidoc.module.draft-js.BlockTree)

#### <a name="apidoc.element.draft-js.BlockTree.generate"></a>[function <span class="apidocSignatureSpan">draft-js.BlockTree.</span>generate (contentState, block, decorator)](#apidoc.element.draft-js.BlockTree.generate)
- description and source-code
```javascript
function generate(contentState, block, decorator) {
  var textLength = block.getLength();
  if (!textLength) {
    return List.of(new DecoratorRange({
      start: 0,
      end: 0,
      decoratorKey: null,
      leaves: List.of(new LeafRange({ start: 0, end: 0 }))
    }));
  }

  var leafSets = [];
  var decorations = decorator ? decorator.getDecorations(block, contentState) : List(Repeat(null, textLength));

  var chars = block.getCharacterList();

  findRangesImmutable(decorations, areEqual, returnTrue, function (start, end) {
    leafSets.push(new DecoratorRange({
      start: start,
      end: end,
      decoratorKey: decorations.get(start),
      leaves: generateLeaves(chars.slice(start, end).toList(), start)
    }));
  });

  return List(leafSets);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.BlockTree.getFingerprint"></a>[function <span class="apidocSignatureSpan">draft-js.BlockTree.</span>getFingerprint (tree)](#apidoc.element.draft-js.BlockTree.getFingerprint)
- description and source-code
```javascript
function getFingerprint(tree) {
  return tree.map(function (leafSet) {
    var decoratorKey = leafSet.get('decoratorKey');
    var fingerprintString = decoratorKey !== null ? decoratorKey + '.' + (leafSet.get('end') - leafSet.get('start')) : '';
    return '' + fingerprintString + '.' + leafSet.get('leaves').size;
  }).join(FINGERPRINT_DELIMITER);
}
```
- example usage
```shell
...

var anchorKey = selection.getAnchorKey();
var anchorTree = editorState.getBlockTree(anchorKey);

// Check the old and new "fingerprints" of the current block to determine
// whether this insertion requires any addition or removal of text nodes,
// in which case we would prevent the native character insertion.
var originalFingerprint = BlockTree.getFingerprint(anchorTree);
var newFingerprint = BlockTree.getFingerprint(newEditorState.getBlockTree(anchorKey));

if (mustPreventDefaultForCharacter(chars) || originalFingerprint !== newFingerprint || nullthrows(newEditorState.getDirectionMap
()).get(anchorKey) !== nullthrows(editorState.getDirectionMap()).get(anchorKey)) {
  e.preventDefault();
  editor.update(newEditorState);
} else {
  newEditorState = EditorState.set(newEditorState, {
...
```



# <a name="apidoc.module.draft-js.CharacterMetadata"></a>[module draft-js.CharacterMetadata](#apidoc.module.draft-js.CharacterMetadata)

#### <a name="apidoc.element.draft-js.CharacterMetadata.CharacterMetadata"></a>[function <span class="apidocSignatureSpan">draft-js.</span>CharacterMetadata ()](#apidoc.element.draft-js.CharacterMetadata.CharacterMetadata)
- description and source-code
```javascript
function CharacterMetadata() {
  _classCallCheck(this, CharacterMetadata);

  return _possibleConstructorReturn(this, _CharacterMetadataRec.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.CharacterMetadata.applyEntity"></a>[function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>applyEntity (record, entityKey)](#apidoc.element.draft-js.CharacterMetadata.applyEntity)
- description and source-code
```javascript
function applyEntity(record, entityKey) {
  var withEntity = record.getEntity() === entityKey ? record : record.set('entity', entityKey);
  return CharacterMetadata.create(withEntity);
}
```
- example usage
```shell
...
'use strict';

var CharacterMetadata = require('./CharacterMetadata');

function applyEntityToContentBlock(contentBlock, start, end, entityKey) {
  var characterList = contentBlock.getCharacterList();
  while (start < end) {
    characterList = characterList.set(start, CharacterMetadata.applyEntity(characterList.get(start), entityKey));
    start++;
  }
  return contentBlock.set('characterList', characterList);
}

module.exports = applyEntityToContentBlock;
...
```

#### <a name="apidoc.element.draft-js.CharacterMetadata.applyStyle"></a>[function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>applyStyle (record, style)](#apidoc.element.draft-js.CharacterMetadata.applyStyle)
- description and source-code
```javascript
function applyStyle(record, style) {
  var withStyle = record.set('style', record.getStyle().add(style));
  return CharacterMetadata.create(withStyle);
}
```
- example usage
```shell
...
    sliceEnd = blockKey === endKey ? endOffset : block.getLength();
  }

  var chars = block.getCharacterList();
  var current;
  while (sliceStart < sliceEnd) {
    current = chars.get(sliceStart);
    chars = chars.set(sliceStart, addOrRemove ? CharacterMetadata.applyStyle(current, inlineStyle) : CharacterMetadata.removeStyle
(current, inlineStyle));
    sliceStart++;
  }

  return block.set('characterList', chars);
});

return contentState.merge({
...
```

#### <a name="apidoc.element.draft-js.CharacterMetadata.create"></a>[function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>create (config)](#apidoc.element.draft-js.CharacterMetadata.create)
- description and source-code
```javascript
function create(config) {
  if (!config) {
    return EMPTY;
  }

  var defaultConfig = { style: EMPTY_SET, entity: null };

  // Fill in unspecified properties, if necessary.
  var configMap = Map(defaultConfig).merge(config);

  var existing = pool.get(configMap);
  if (existing) {
    return existing;
  }

  var newCharacter = new CharacterMetadata(configMap);
  pool = pool.set(configMap, newCharacter);
  return newCharacter;
}
```
- example usage
```shell
...

var _extends = _assign || function (target) { for (var i = 1; i < arguments.length; i++) { var source = arguments[i]; for (var key
 in source) { if (Object.prototype.hasOwnProperty.call(source, key)) { target[key] = source[key]; } } } return target; };

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class
 as a function"); } }

function _possibleConstructorReturn(self, call) { if (!self) { throw new ReferenceError("this hasn't been initialised - super()
hasn't been called"); } return call && (typeof call === "object" || typeof call === "function") ? call : self; }

function _inherits(subClass, superClass) { if (typeof superClass !== "function" && superClass !== null) { throw new TypeError("Super
 expression must either be null or a function, not " + typeof superClass); } subClass.prototype = Object.create(superClass && superClass
.prototype, { constructor: { value: subClass, enumerable: false, writable: true, configurable: true } }); if (superClass) Object
.setPrototypeOf ? Object.setPrototypeOf(subClass, superClass) : subClass.__proto__ = superClass; }

var DraftEditorBlock = require('./DraftEditorBlock.react');
var DraftOffsetKey = require('./DraftOffsetKey');
var EditorState = require('./EditorState');
var React = require('react');

var cx = require('fbjs/lib/cx');
...
```

#### <a name="apidoc.element.draft-js.CharacterMetadata.removeStyle"></a>[function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.</span>removeStyle (record, style)](#apidoc.element.draft-js.CharacterMetadata.removeStyle)
- description and source-code
```javascript
function removeStyle(record, style) {
  var withoutStyle = record.set('style', record.getStyle().remove(style));
  return CharacterMetadata.create(withoutStyle);
}
```
- example usage
```shell
...
    sliceEnd = blockKey === endKey ? endOffset : block.getLength();
  }

  var chars = block.getCharacterList();
  var current;
  while (sliceStart < sliceEnd) {
    current = chars.get(sliceStart);
    chars = chars.set(sliceStart, addOrRemove ? CharacterMetadata.applyStyle(current, inlineStyle) : CharacterMetadata.removeStyle
(current, inlineStyle));
    sliceStart++;
  }

  return block.set('characterList', chars);
});

return contentState.merge({
...
```



# <a name="apidoc.module.draft-js.CharacterMetadata.prototype"></a>[module draft-js.CharacterMetadata.prototype](#apidoc.module.draft-js.CharacterMetadata.prototype)

#### <a name="apidoc.element.draft-js.CharacterMetadata.prototype.getEntity"></a>[function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.prototype.</span>getEntity ()](#apidoc.element.draft-js.CharacterMetadata.prototype.getEntity)
- description and source-code
```javascript
function getEntity() {
  return this.get('entity');
}
```
- example usage
```shell
...
function convertFromDraftStateToRaw(contentState) {
var entityStorageKey = 0;
var entityStorageMap = {};
var rawBlocks = [];

contentState.getBlockMap().forEach(function (block, blockKey) {
  block.findEntityRanges(function (character) {
    return character.getEntity() !== null;
  }, function (start) {
    // Stringify to maintain order of otherwise numeric keys.
    var stringifiedEntityKey = DraftStringKey.stringify(block.getEntityAt(start));
    if (!entityStorageMap.hasOwnProperty(stringifiedEntityKey)) {
      entityStorageMap[stringifiedEntityKey] = '' + entityStorageKey++;
    }
  });
...
```

#### <a name="apidoc.element.draft-js.CharacterMetadata.prototype.getStyle"></a>[function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.prototype.</span>getStyle ()](#apidoc.element.draft-js.CharacterMetadata.prototype.getStyle)
- description and source-code
```javascript
function getStyle() {
  return this.get('style');
}
```
- example usage
```shell
...

/**
 * Generate LeafRange records for a given character list.
 */
function generateLeaves(characters, offset) {
var leaves = [];
var inlineStyles = characters.map(function (c) {
  return c.getStyle();
}).toList();
findRangesImmutable(inlineStyles, areEqual, returnTrue, function (start, end) {
  leaves.push(new LeafRange({
    start: start + offset,
    end: end + offset
  }));
});
...
```

#### <a name="apidoc.element.draft-js.CharacterMetadata.prototype.hasStyle"></a>[function <span class="apidocSignatureSpan">draft-js.CharacterMetadata.prototype.</span>hasStyle (style)](#apidoc.element.draft-js.CharacterMetadata.prototype.hasStyle)
- description and source-code
```javascript
function hasStyle(style) {
  return this.getStyle().has(style);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.CompositeDecorator"></a>[module draft-js.CompositeDecorator](#apidoc.module.draft-js.CompositeDecorator)

#### <a name="apidoc.element.draft-js.CompositeDecorator.CompositeDecorator"></a>[function <span class="apidocSignatureSpan">draft-js.</span>CompositeDecorator (decorators)](#apidoc.element.draft-js.CompositeDecorator.CompositeDecorator)
- description and source-code
```javascript
function CompositeDraftDecorator(decorators) {
  _classCallCheck(this, CompositeDraftDecorator);

  // Copy the decorator array, since we use this array order to determine
  // precedence of decoration matching. If the array is mutated externally,
  // we don't want to be affected here.
  this._decorators = decorators.slice();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.CompositeDecorator.prototype"></a>[module draft-js.CompositeDecorator.prototype](#apidoc.module.draft-js.CompositeDecorator.prototype)

#### <a name="apidoc.element.draft-js.CompositeDecorator.prototype.getComponentForKey"></a>[function <span class="apidocSignatureSpan">draft-js.CompositeDecorator.prototype.</span>getComponentForKey (key)](#apidoc.element.draft-js.CompositeDecorator.prototype.getComponentForKey)
- description and source-code
```javascript
function getComponentForKey(key) {
  var componentKey = parseInt(key.split(DELIMITER)[0], 10);
  return this._decorators[componentKey].component;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.CompositeDecorator.prototype.getDecorations"></a>[function <span class="apidocSignatureSpan">draft-js.CompositeDecorator.prototype.</span>getDecorations (block, contentState)](#apidoc.element.draft-js.CompositeDecorator.prototype.getDecorations)
- description and source-code
```javascript
function getDecorations(block, contentState) {
  var decorations = Array(block.getText().length).fill(null);

  this._decorators.forEach(function ( /*object*/decorator, /*number*/ii) {
    var counter = 0;
    var strategy = decorator.strategy;
    var callback = function callback( /*number*/start, /*number*/end) {
      // Find out if any of our matching range is already occupied
      // by another decorator. If so, discard the match. Otherwise, store
      // the component key for rendering.
      if (canOccupySlice(decorations, start, end)) {
        occupySlice(decorations, start, end, ii + DELIMITER + counter);
        counter++;
      }
    };
    strategy(block, callback, contentState);
  });

  return List(decorations);
}
```
- example usage
```shell
...
    end: 0,
    decoratorKey: null,
    leaves: List.of(new LeafRange({ start: 0, end: 0 }))
  }));
}

var leafSets = [];
var decorations = decorator ? decorator.getDecorations(block, contentState) : List(Repeat(null, textLength));

var chars = block.getCharacterList();

findRangesImmutable(decorations, areEqual, returnTrue, function (start, end) {
  leafSets.push(new DecoratorRange({
    start: start,
    end: end,
...
```

#### <a name="apidoc.element.draft-js.CompositeDecorator.prototype.getPropsForKey"></a>[function <span class="apidocSignatureSpan">draft-js.CompositeDecorator.prototype.</span>getPropsForKey (key)](#apidoc.element.draft-js.CompositeDecorator.prototype.getPropsForKey)
- description and source-code
```javascript
function getPropsForKey(key) {
  var componentKey = parseInt(key.split(DELIMITER)[0], 10);
  return this._decorators[componentKey].props;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.ContentBlock"></a>[module draft-js.ContentBlock](#apidoc.module.draft-js.ContentBlock)

#### <a name="apidoc.element.draft-js.ContentBlock.ContentBlock"></a>[function <span class="apidocSignatureSpan">draft-js.</span>ContentBlock ()](#apidoc.element.draft-js.ContentBlock.ContentBlock)
- description and source-code
```javascript
function ContentBlock() {
  _classCallCheck(this, ContentBlock);

  return _possibleConstructorReturn(this, _ContentBlockRecord.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.ContentBlock.prototype"></a>[module draft-js.ContentBlock.prototype](#apidoc.module.draft-js.ContentBlock.prototype)

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.findEntityRanges"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>findEntityRanges (filterFn, callback)](#apidoc.element.draft-js.ContentBlock.prototype.findEntityRanges)
- description and source-code
```javascript
function findEntityRanges(filterFn, callback) {
  findRangesImmutable(this.getCharacterList(), haveEqualEntity, filterFn, callback);
}
```
- example usage
```shell
...

function convertFromDraftStateToRaw(contentState) {
var entityStorageKey = 0;
var entityStorageMap = {};
var rawBlocks = [];

contentState.getBlockMap().forEach(function (block, blockKey) {
  block.findEntityRanges(function (character) {
    return character.getEntity() !== null;
  }, function (start) {
    // Stringify to maintain order of otherwise numeric keys.
    var stringifiedEntityKey = DraftStringKey.stringify(block.getEntityAt(start));
    if (!entityStorageMap.hasOwnProperty(stringifiedEntityKey)) {
      entityStorageMap[stringifiedEntityKey] = '' + entityStorageKey++;
    }
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.findStyleRanges"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>findStyleRanges (filterFn, callback)](#apidoc.element.draft-js.ContentBlock.prototype.findStyleRanges)
- description and source-code
```javascript
function findStyleRanges(filterFn, callback) {
  findRangesImmutable(this.getCharacterList(), haveEqualStyle, filterFn, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getCharacterList"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getCharacterList ()](#apidoc.element.draft-js.ContentBlock.prototype.getCharacterList)
- description and source-code
```javascript
function getCharacterList() {
  return this.get('characterList');
}
```
- example usage
```shell
...
    leaves: List.of(new LeafRange({ start: 0, end: 0 }))
  }));
}

var leafSets = [];
var decorations = decorator ? decorator.getDecorations(block, contentState) : List(Repeat(null, textLength));

var chars = block.getCharacterList();

findRangesImmutable(decorations, areEqual, returnTrue, function (start, end) {
  leafSets.push(new DecoratorRange({
    start: start,
    end: end,
    decoratorKey: decorations.get(start),
    leaves: generateLeaves(chars.slice(start, end).toList(), start)
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getData"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getData ()](#apidoc.element.draft-js.ContentBlock.prototype.getData)
- description and source-code
```javascript
function getData() {
  return this.get('data');
}
```
- example usage
```shell
...
  rawBlocks.push({
    key: blockKey,
    text: block.getText(),
    type: block.getType(),
    depth: block.getDepth(),
    inlineStyleRanges: encodeInlineStyleRanges(block),
    entityRanges: encodeEntityRanges(block, entityStorageMap),
    data: block.getData().toObject()
  });
});

// Flip storage map so that our storage keys map to global
// DraftEntity keys.
var entityKeys = Object.keys(entityStorageMap);
var flippedStorageMap = {};
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getDepth"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getDepth ()](#apidoc.element.draft-js.ContentBlock.prototype.getDepth)
- description and source-code
```javascript
function getDepth() {
  return this.get('depth');
}
```
- example usage
```shell
...
};

var configForType = blockRenderMap.get(blockType);
var wrapperTemplate = configForType.wrapper;

var _Element = configForType.element || blockRenderMap.get('unstyled').element;

var depth = _block.getDepth();
var className = this.props.blockStyleFn(_block);

// List items are special snowflakes, since we handle nesting and
// counters manually.
if (_Element === 'li') {
  var shouldResetCount = lastWrapperTemplate !== wrapperTemplate || currentDepth === null || depth > currentDepth;
  className = joinClasses(className, getListItemClasses(blockType, depth, shouldResetCount, direction));
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getEntityAt"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getEntityAt (offset)](#apidoc.element.draft-js.ContentBlock.prototype.getEntityAt)
- description and source-code
```javascript
function getEntityAt(offset) {
  var character = this.getCharacterList().get(offset);
  return character ? character.getEntity() : null;
}
```
- example usage
```shell
...
  var rawBlocks = [];

  contentState.getBlockMap().forEach(function (block, blockKey) {
block.findEntityRanges(function (character) {
  return character.getEntity() !== null;
}, function (start) {
  // Stringify to maintain order of otherwise numeric keys.
  var stringifiedEntityKey = DraftStringKey.stringify(block.getEntityAt(start));
  if (!entityStorageMap.hasOwnProperty(stringifiedEntityKey)) {
    entityStorageMap[stringifiedEntityKey] = '' + entityStorageKey++;
  }
});

rawBlocks.push({
  key: blockKey,
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getInlineStyleAt"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getInlineStyleAt (offset)](#apidoc.element.draft-js.ContentBlock.prototype.getInlineStyleAt)
- description and source-code
```javascript
function getInlineStyleAt(offset) {
  var character = this.getCharacterList().get(offset);
  return character ? character.getStyle() : EMPTY_SET;
}
```
- example usage
```shell
...

// Immutable or segmented entities cannot properly be handled by the
// default browser undo, so we have to use a different change type to
// force using our internal undo method instead of falling through to the
// native browser undo.
var changeType = preserveEntity ? 'spellcheck-change' : 'apply-entity';

var newContent = DraftModifier.replaceText(content, targetRange, domText, block.getInlineStyleAt(start), preserveEntity ? block.
getEntityAt(start) : null);

var anchorOffset, focusOffset, startOffset, endOffset;

if (isGecko) {
  // Firefox selection does not change while the context menu is open, so
  // we preserve the anchor and focus values of the DOM selection.
  anchorOffset = domSelection.anchorOffset;
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getKey"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getKey ()](#apidoc.element.draft-js.ContentBlock.prototype.getKey)
- description and source-code
```javascript
function getKey() {
  return this.get('key');
}
```
- example usage
```shell
...
    var blocksAsArray = content.getBlocksAsArray();
    var processedBlocks = [];
    var currentDepth = null;
    var lastWrapperTemplate = null;

    for (var ii = 0; ii < blocksAsArray.length; ii++) {
var _block = blocksAsArray[ii];
var key = _block.getKey();
var blockType = _block.getType();

var customRenderer = blockRendererFn(_block);
var CustomComponent = void 0,
    customProps = void 0,
    customEditable = void 0;
if (customRenderer) {
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getLength"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getLength ()](#apidoc.element.draft-js.ContentBlock.prototype.getLength)
- description and source-code
```javascript
function getLength() {
  return this.getText().length;
}
```
- example usage
```shell
...
var DecoratorRange = Record(defaultDecoratorRange);

var BlockTree = {
/**
 * Generate a block tree for a given ContentBlock/decorator pair.
 */
generate: function generate(contentState, block, decorator) {
  var textLength = block.getLength();
  if (!textLength) {
    return List.of(new DecoratorRange({
      start: 0,
      end: 0,
      decoratorKey: null,
      leaves: List.of(new LeafRange({ start: 0, end: 0 }))
    }));
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getText"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getText ()](#apidoc.element.draft-js.ContentBlock.prototype.getText)
- description and source-code
```javascript
function getText() {
  return this.get('text');
}
```
- example usage
```shell
...
  }

  if (editor._internalDrag) {
    editor.update(moveText(editorState, dropSelection));
    return;
  }

  editor.update(insertTextAtSelection(editorState, dropSelection, data.getText()));
}

};

function moveText(editorState, targetSelection) {
var newContentState = DraftModifier.moveText(editorState.getCurrentContent(), editorState.getSelection(), targetSelection);
return EditorState.push(editorState, newContentState, 'insert-fragment');
...
```

#### <a name="apidoc.element.draft-js.ContentBlock.prototype.getType"></a>[function <span class="apidocSignatureSpan">draft-js.ContentBlock.prototype.</span>getType ()](#apidoc.element.draft-js.ContentBlock.prototype.getType)
- description and source-code
```javascript
function getType() {
  return this.get('type');
}
```
- example usage
```shell
...
    var processedBlocks = [];
    var currentDepth = null;
    var lastWrapperTemplate = null;

    for (var ii = 0; ii < blocksAsArray.length; ii++) {
var _block = blocksAsArray[ii];
var key = _block.getKey();
var blockType = _block.getType();

var customRenderer = blockRendererFn(_block);
var CustomComponent = void 0,
    customProps = void 0,
    customEditable = void 0;
if (customRenderer) {
  CustomComponent = customRenderer.component;
...
```



# <a name="apidoc.module.draft-js.ContentState"></a>[module draft-js.ContentState](#apidoc.module.draft-js.ContentState)

#### <a name="apidoc.element.draft-js.ContentState.ContentState"></a>[function <span class="apidocSignatureSpan">draft-js.</span>ContentState ()](#apidoc.element.draft-js.ContentState.ContentState)
- description and source-code
```javascript
function ContentState() {
  _classCallCheck(this, ContentState);

  return _possibleConstructorReturn(this, _ContentStateRecord.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.createFromBlockArray"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.</span>createFromBlockArray ( // TODO: update flow type when we completely deprecate the old entity API blocks, entityMap)](#apidoc.element.draft-js.ContentState.createFromBlockArray)
- description and source-code
```javascript
function createFromBlockArray( // TODO: update flow type when we completely deprecate the old entity API blocks, entityMap) {
  // TODO: remove this when we completely deprecate the old entity API
  var theBlocks = Array.isArray(blocks) ? blocks : blocks.contentBlocks;
  var blockMap = BlockMapBuilder.createFromArray(theBlocks);
  var selectionState = blockMap.isEmpty() ? new SelectionState() : SelectionState.createEmpty(blockMap.first().getKey());
  return new ContentState({
    blockMap: blockMap,
    entityMap: entityMap || DraftEntity,
    selectionBefore: selectionState,
    selectionAfter: selectionState
  });
}
```
- example usage
```shell
...

    var entities = decodeEntityRanges(text, filteredEntityRanges);
    var characterList = createCharacterList(inlineStyles, entities);

    return new ContentBlock({ key: key, type: type, text: text, depth: depth, characterList: characterList, data: data });
  });

  return ContentState.createFromBlockArray(contentBlocks);
}

module.exports = convertFromRawToDraftState;
...
```

#### <a name="apidoc.element.draft-js.ContentState.createFromText"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.</span>createFromText (text)](#apidoc.element.draft-js.ContentState.createFromText)
- description and source-code
```javascript
function createFromText(text) {
  var delimiter = arguments.length <= 1 || arguments[1] === undefined ? /\r\n?|\n/g : arguments[1];

  var strings = text.split(delimiter);
  var blocks = strings.map(function (block) {
    block = sanitizeDraftText(block);
    return new ContentBlock({
      key: generateRandomKey(),
      text: block,
      type: 'unstyled',
      characterList: List(Repeat(CharacterMetadata.EMPTY, block.length))
    });
  });
  return ContentState.createFromBlockArray(blocks);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.ContentState.prototype"></a>[module draft-js.ContentState.prototype](#apidoc.module.draft-js.ContentState.prototype)

#### <a name="apidoc.element.draft-js.ContentState.prototype.addEntity"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>addEntity (instance)](#apidoc.element.draft-js.ContentState.prototype.addEntity)
- description and source-code
```javascript
function addEntity(instance) {
  // TODO: update this when we fully remove DraftEntity
  DraftEntity.__add(instance);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.createEntity"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>createEntity (type, mutability, data)](#apidoc.element.draft-js.ContentState.prototype.createEntity)
- description and source-code
```javascript
function createEntity(type, mutability, data) {
  // TODO: update this when we fully remove DraftEntity
  DraftEntity.__create(type, mutability, data);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getBlockAfter"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockAfter (key)](#apidoc.element.draft-js.ContentState.prototype.getBlockAfter)
- description and source-code
```javascript
function getBlockAfter(key) {
  return this.getBlockMap().skipUntil(function (_, k) {
    return k === key;
  }).skip(1).first();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getBlockBefore"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockBefore (key)](#apidoc.element.draft-js.ContentState.prototype.getBlockBefore)
- description and source-code
```javascript
function getBlockBefore(key) {
  return this.getBlockMap().reverse().skipUntil(function (_, k) {
    return k === key;
  }).skip(1).first();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getBlockForKey"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockForKey (key)](#apidoc.element.draft-js.ContentState.prototype.getBlockForKey)
- description and source-code
```javascript
function getBlockForKey(key) {
  var block = this.getBlockMap().get(key);
  return block;
}
```
- example usage
```shell
...
  cut: function cut(editorState) {
var content = editorState.getCurrentContent();
var selection = editorState.getSelection();
var targetRange = null;

if (selection.isCollapsed()) {
  var anchorKey = selection.getAnchorKey();
  var blockEnd = content.getBlockForKey(anchorKey).getLength();

  if (blockEnd === selection.getAnchorOffset()) {
    return editorState;
  }

  targetRange = selection.set('focusOffset', blockEnd);
} else {
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getBlockMap"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlockMap ()](#apidoc.element.draft-js.ContentState.prototype.getBlockMap)
- description and source-code
```javascript
function getBlockMap() {
  return this.get('blockMap');
}
```
- example usage
```shell
...

remove: function remove(contentState, selectionState, inlineStyle) {
  return modifyInlineStyle(contentState, selectionState, inlineStyle, false);
}
};

function modifyInlineStyle(contentState, selectionState, inlineStyle, addOrRemove) {
var blockMap = contentState.getBlockMap();
var startKey = selectionState.getStartKey();
var startOffset = selectionState.getStartOffset();
var endKey = selectionState.getEndKey();
var endOffset = selectionState.getEndOffset();

var newBlocks = blockMap.skipUntil(function (_, k) {
  return k === startKey;
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getBlocksAsArray"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getBlocksAsArray ()](#apidoc.element.draft-js.ContentState.prototype.getBlocksAsArray)
- description and source-code
```javascript
function getBlocksAsArray() {
  return this.getBlockMap().toArray();
}
```
- example usage
```shell
...

var content = editorState.getCurrentContent();
var selection = editorState.getSelection();
var forceSelection = editorState.mustForceSelection();
var decorator = editorState.getDecorator();
var directionMap = nullthrows(editorState.getDirectionMap());

var blocksAsArray = content.getBlocksAsArray();
var processedBlocks = [];
var currentDepth = null;
var lastWrapperTemplate = null;

for (var ii = 0; ii < blocksAsArray.length; ii++) {
  var _block = blocksAsArray[ii];
  var key = _block.getKey();
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getEntity"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getEntity (key)](#apidoc.element.draft-js.ContentState.prototype.getEntity)
- description and source-code
```javascript
function getEntity(key) {
  // TODO: update this when we fully remove DraftEntity
  return DraftEntity.__get(key);
}
```
- example usage
```shell
...
function convertFromDraftStateToRaw(contentState) {
var entityStorageKey = 0;
var entityStorageMap = {};
var rawBlocks = [];

contentState.getBlockMap().forEach(function (block, blockKey) {
  block.findEntityRanges(function (character) {
    return character.getEntity() !== null;
  }, function (start) {
    // Stringify to maintain order of otherwise numeric keys.
    var stringifiedEntityKey = DraftStringKey.stringify(block.getEntityAt(start));
    if (!entityStorageMap.hasOwnProperty(stringifiedEntityKey)) {
      entityStorageMap[stringifiedEntityKey] = '' + entityStorageKey++;
    }
  });
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getEntityMap"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getEntityMap ()](#apidoc.element.draft-js.ContentState.prototype.getEntityMap)
- description and source-code
```javascript
function getEntityMap() {
  // TODO: update this when we fully remove DraftEntity
  return DraftEntity;
}
```
- example usage
```shell
...
 */

'use strict';

var addEntityToEntityMap = require('./addEntityToEntityMap');

function addEntityToContentState(contentState, instance) {
  return contentState.set('entityMap', addEntityToEntityMap(contentState.getEntityMap(), instance));
}

module.exports = addEntityToContentState;
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getFirstBlock"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getFirstBlock ()](#apidoc.element.draft-js.ContentState.prototype.getFirstBlock)
- description and source-code
```javascript
function getFirstBlock() {
  return this.getBlockMap().first();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getKeyAfter"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getKeyAfter (key)](#apidoc.element.draft-js.ContentState.prototype.getKeyAfter)
- description and source-code
```javascript
function getKeyAfter(key) {
  return this.getBlockMap().keySeq().skipUntil(function (v) {
    return v === key;
  }).skip(1).first();
}
```
- example usage
```shell
...

  var focusKey = key;
  var focusOffset;

  var block = content.getBlockForKey(key);

  if (maxDistance > block.getText().length - offset) {
    focusKey = content.getKeyAfter(key);
    focusOffset = 0;
  } else {
    focusOffset = offset + maxDistance;
  }

  return selection.merge({ focusKey: focusKey, focusOffset: focusOffset });
}
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getKeyBefore"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getKeyBefore (key)](#apidoc.element.draft-js.ContentState.prototype.getKeyBefore)
- description and source-code
```javascript
function getKeyBefore(key) {
  return this.getBlockMap().reverse().keySeq().skipUntil(function (v) {
    return v === key;
  }).skip(1).first();
}
```
- example usage
```shell
...
var key = selection.getStartKey();
var offset = selection.getStartOffset();

var focusKey = key;
var focusOffset = 0;

if (maxDistance > offset) {
  var keyBefore = content.getKeyBefore(key);
  if (keyBefore == null) {
    focusKey = key;
  } else {
    focusKey = keyBefore;
    var blockBefore = content.getBlockForKey(keyBefore);
    focusOffset = blockBefore.getText().length;
  }
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getLastBlock"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getLastBlock ()](#apidoc.element.draft-js.ContentState.prototype.getLastBlock)
- description and source-code
```javascript
function getLastBlock() {
  return this.getBlockMap().last();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getLastCreatedEntityKey"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getLastCreatedEntityKey ()](#apidoc.element.draft-js.ContentState.prototype.getLastCreatedEntityKey)
- description and source-code
```javascript
function getLastCreatedEntityKey() {
  // TODO: update this when we fully remove DraftEntity
  return DraftEntity.__getLastCreatedEntityKey();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getPlainText"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getPlainText (delimiter)](#apidoc.element.draft-js.ContentState.prototype.getPlainText)
- description and source-code
```javascript
function getPlainText(delimiter) {
  return this.getBlockMap().map(function (block) {
    return block ? block.getText() : '';
  }).join(delimiter || '\n');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getSelectionAfter"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getSelectionAfter ()](#apidoc.element.draft-js.ContentState.prototype.getSelectionAfter)
- description and source-code
```javascript
function getSelectionAfter() {
  return this.get('selectionAfter');
}
```
- example usage
```shell
...
    focusOffset = endOffset + charDelta;
  }

  // Segmented entities are completely or partially removed when their
  // text content changes. For this case we do not want any text to be selected
  // after the change, so we are not merging the selection.
  var contentWithAdjustedDOMSelection = newContent.merge({
    selectionBefore: content.getSelectionAfter(),
    selectionAfter: selection.merge({ anchorOffset: anchorOffset, focusOffset: focusOffset })
  });

  editor.update(EditorState.push(editorState, contentWithAdjustedDOMSelection, changeType));
}

module.exports = editOnInput;
...
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.getSelectionBefore"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>getSelectionBefore ()](#apidoc.element.draft-js.ContentState.prototype.getSelectionBefore)
- description and source-code
```javascript
function getSelectionBefore() {
  return this.get('selectionBefore');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.hasText"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>hasText ()](#apidoc.element.draft-js.ContentState.prototype.hasText)
- description and source-code
```javascript
function hasText() {
  var blockMap = this.getBlockMap();
  return blockMap.size > 1 || blockMap.first().getLength() > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.mergeEntityData"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>mergeEntityData (key, toMerge)](#apidoc.element.draft-js.ContentState.prototype.mergeEntityData)
- description and source-code
```javascript
function mergeEntityData(key, toMerge) {
  // TODO: update this when we fully remove DraftEntity
  DraftEntity.__mergeData(key, toMerge);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.ContentState.prototype.replaceEntityData"></a>[function <span class="apidocSignatureSpan">draft-js.ContentState.prototype.</span>replaceEntityData (key, newData)](#apidoc.element.draft-js.ContentState.prototype.replaceEntityData)
- description and source-code
```javascript
function replaceEntityData(key, newData) {
  // TODO: update this when we fully remove DraftEntity
  DraftEntity.__replaceData(key, newData);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.ContentStateInlineStyle"></a>[module draft-js.ContentStateInlineStyle](#apidoc.module.draft-js.ContentStateInlineStyle)

#### <a name="apidoc.element.draft-js.ContentStateInlineStyle.add"></a>[function <span class="apidocSignatureSpan">draft-js.ContentStateInlineStyle.</span>add (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.ContentStateInlineStyle.add)
- description and source-code
```javascript
function add(contentState, selectionState, inlineStyle) {
  return modifyInlineStyle(contentState, selectionState, inlineStyle, true);
}
```
- example usage
```shell
...
function getBlockMapSupportedTags(blockRenderMap) {
var unstyledElement = blockRenderMap.get('unstyled').element;
var tags = new Set([]);

blockRenderMap.forEach(function (draftBlock) {
  if (draftBlock.aliasedElements) {
    draftBlock.aliasedElements.forEach(function (tag) {
      tags = tags.add(tag);
    });
  }

  tags = tags.add(draftBlock.element);
});

return tags.filter(function (tag) {
...
```

#### <a name="apidoc.element.draft-js.ContentStateInlineStyle.remove"></a>[function <span class="apidocSignatureSpan">draft-js.ContentStateInlineStyle.</span>remove (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.ContentStateInlineStyle.remove)
- description and source-code
```javascript
function remove(contentState, selectionState, inlineStyle) {
  return modifyInlineStyle(contentState, selectionState, inlineStyle, false);
}
```
- example usage
```shell
...
var fontWeight = htmlElement.style.fontWeight;
var fontStyle = htmlElement.style.fontStyle;
var textDecoration = htmlElement.style.textDecoration;

if (boldValues.indexOf(fontWeight) >= 0) {
  style.add('BOLD');
} else if (notBoldValues.indexOf(fontWeight) >= 0) {
  style.remove('BOLD');
}

if (fontStyle === 'italic') {
  style.add('ITALIC');
} else if (fontStyle === 'normal') {
  style.remove('ITALIC');
}
...
```



# <a name="apidoc.module.draft-js.DraftEditorCompositionHandler"></a>[module draft-js.DraftEditorCompositionHandler](#apidoc.module.draft-js.DraftEditorCompositionHandler)

#### <a name="apidoc.element.draft-js.DraftEditorCompositionHandler.onBeforeInput"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onBeforeInput (editor, e)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onBeforeInput)
- description and source-code
```javascript
function onBeforeInput(editor, e) {
  textInputData = (textInputData || '') + e.data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorCompositionHandler.onCompositionEnd"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onCompositionEnd (editor)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onCompositionEnd)
- description and source-code
```javascript
function onCompositionEnd(editor) {
  resolved = false;
  stillComposing = false;
  setTimeout(function () {
    if (!resolved) {
      DraftEditorCompositionHandler.resolveComposition(editor);
    }
  }, RESOLVE_DELAY);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorCompositionHandler.onCompositionStart"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onCompositionStart (editor)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onCompositionStart)
- description and source-code
```javascript
function onCompositionStart(editor) {
  stillComposing = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorCompositionHandler.onKeyDown"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onKeyDown (editor, e)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onKeyDown)
- description and source-code
```javascript
function onKeyDown(editor, e) {
  if (!stillComposing) {
    // If a keydown event is received after compositionend but before the
    // 20ms timer expires (ex: type option-E then backspace, or type A then
    // backspace in 2-Set Korean), we should immediately resolve the
    // composition and reinterpret the key press in edit mode.
    DraftEditorCompositionHandler.resolveComposition(editor);
    editor._onKeyDown(e);
    return;
  }
  if (e.which === Keys.RIGHT || e.which === Keys.LEFT) {
    e.preventDefault();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorCompositionHandler.onKeyPress"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>onKeyPress (editor, e)](#apidoc.element.draft-js.DraftEditorCompositionHandler.onKeyPress)
- description and source-code
```javascript
function onKeyPress(editor, e) {
  if (e.which === Keys.RETURN) {
    e.preventDefault();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorCompositionHandler.resolveComposition"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorCompositionHandler.</span>resolveComposition (editor)](#apidoc.element.draft-js.DraftEditorCompositionHandler.resolveComposition)
- description and source-code
```javascript
function resolveComposition(editor) {
  if (stillComposing) {
    return;
  }

  resolved = true;
  var composedChars = textInputData;
  textInputData = '';

  var editorState = EditorState.set(editor._latestEditorState, {
    inCompositionMode: false
  });

  var currentStyle = editorState.getCurrentInlineStyle();
  var entityKey = getEntityKeyForSelection(editorState.getCurrentContent(), editorState.getSelection());

  var mustReset = !composedChars || isSelectionAtLeafStart(editorState) || currentStyle.size > 0 || entityKey !== null;

  if (mustReset) {
    editor.restoreEditorDOM();
  }

  editor.exitCurrentMode();

  if (composedChars) {
    // If characters have been composed, re-rendering with the update
    // is sufficient to reset the editor.
    var contentState = DraftModifier.replaceText(editorState.getCurrentContent(), editorState.getSelection(), composedChars, currentStyle
, entityKey);
    editor.update(EditorState.push(editorState, contentState, 'insert-characters'));
    return;
  }

  if (mustReset) {
    editor.update(EditorState.set(editorState, {
      nativelyRenderedContent: null,
      forceSelection: true
    }));
  }
}
```
- example usage
```shell
...
 * Google Input Tools on Windows 8.1 fires 'compositionend' three times.
 */
onCompositionEnd: function onCompositionEnd(editor) {
  resolved = false;
  stillComposing = false;
  setTimeout(function () {
    if (!resolved) {
      DraftEditorCompositionHandler.resolveComposition(editor);
    }
  }, RESOLVE_DELAY);
},

/**
 * In Safari, keydown events may fire when committing compositions. If
 * the arrow keys are used to commit, prevent default so that the cursor
...
```



# <a name="apidoc.module.draft-js.DraftEditorContents_react"></a>[module draft-js.DraftEditorContents_react](#apidoc.module.draft-js.DraftEditorContents_react)

#### <a name="apidoc.element.draft-js.DraftEditorContents_react.DraftEditorContents_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorContents_react ()](#apidoc.element.draft-js.DraftEditorContents_react.DraftEditorContents_react)
- description and source-code
```javascript
function DraftEditorContents() {
  _classCallCheck(this, DraftEditorContents);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorContents_react.prototype"></a>[module draft-js.DraftEditorContents_react.prototype](#apidoc.module.draft-js.DraftEditorContents_react.prototype)

#### <a name="apidoc.element.draft-js.DraftEditorContents_react.prototype.render"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorContents_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorContents_react.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props;
  var blockRenderMap = _props.blockRenderMap;
  var blockRendererFn = _props.blockRendererFn;
  var customStyleMap = _props.customStyleMap;
  var customStyleFn = _props.customStyleFn;
  var editorState = _props.editorState;


  var content = editorState.getCurrentContent();
  var selection = editorState.getSelection();
  var forceSelection = editorState.mustForceSelection();
  var decorator = editorState.getDecorator();
  var directionMap = nullthrows(editorState.getDirectionMap());

  var blocksAsArray = content.getBlocksAsArray();
  var processedBlocks = [];
  var currentDepth = null;
  var lastWrapperTemplate = null;

  for (var ii = 0; ii < blocksAsArray.length; ii++) {
    var _block = blocksAsArray[ii];
    var key = _block.getKey();
    var blockType = _block.getType();

    var customRenderer = blockRendererFn(_block);
    var CustomComponent = void 0,
        customProps = void 0,
        customEditable = void 0;
    if (customRenderer) {
      CustomComponent = customRenderer.component;
      customProps = customRenderer.props;
      customEditable = customRenderer.editable;
    }

    var direction = directionMap.get(key);
    var offsetKey = DraftOffsetKey.encode(key, 0, 0);
    var componentProps = {
      contentState: content,
      block: _block,
      blockProps: customProps,
      customStyleMap: customStyleMap,
      customStyleFn: customStyleFn,
      decorator: decorator,
      direction: direction,
      forceSelection: forceSelection,
      key: key,
      offsetKey: offsetKey,
      selection: selection,
      tree: editorState.getBlockTree(key)
    };

    var configForType = blockRenderMap.get(blockType);
    var wrapperTemplate = configForType.wrapper;

    var _Element = configForType.element || blockRenderMap.get('unstyled').element;

    var depth = _block.getDepth();
    var className = this.props.blockStyleFn(_block);

    // List items are special snowflakes, since we handle nesting and
    // counters manually.
    if (_Element === 'li') {
      var shouldResetCount = lastWrapperTemplate !== wrapperTemplate || currentDepth === null || depth > currentDepth;
      className = joinClasses(className, getListItemClasses(blockType, depth, shouldResetCount, direction));
    }

    var Component = CustomComponent || DraftEditorBlock;
    var childProps = {
      className: className,
      'data-block': true,
      'data-editor': this.props.editorKey,
      'data-offset-key': offsetKey,
      key: key
    };
    if (customEditable !== undefined) {
      childProps = _extends({}, childProps, {
        contentEditable: customEditable,
        suppressContentEditableWarning: true
      });
    }

    var child = React.createElement(_Element, childProps, React.createElement(Component, componentProps));

    processedBlocks.push({
      block: child,
      wrapperTemplate: wrapperTemplate,
      key: key,
      offsetKey: offsetKey
    });

    if (wrapperTemplate) {
      currentDepth = _block.getDepth();
    } else {
      currentDepth = null;
    }
    lastWrapperTemplate = wrapperTemplate;
  }

  // Group contiguous runs of blocks that have the same wrapperTemplate
  var outputBlocks = [];
  for (var _ii = 0; _ii < processedBlocks.length;) {
    var info = processedBlocks[_ii];
    if (info.wrapperTemplate) {
      var blocks = [];
      do {
        blocks.push(processedBlocks[_ii].block);
        _ii++;
      } while (_ii < processedBlocks.length && processedBlocks[_ii].wrapperTemplate === info.wrapperTemplate);
      var wrapperElement = React.cloneElement(info.wrapperTemplate, {
        key: info.key + '-wrap',
        'data-offset-key': info.offsetKey
      }, blocks);
      outputBlocks.push(wrapperElement);
    } else {
      outputBlocks.push(info.block);
      _ii++;
    }
  }

  return React.createElement(
    'div',
    { 'data-contents': 'true' },
    outputBlocks
  );
}
```
- example usage
```shell
...
  render() {
    return (
        <Editor editorState={this.state.editorState} onChange={this.onChange} />
    );
  }
}

ReactDOM.render(
  <MyEditor />,
  document.getElementById('container')
);
'''

Because Draft.js supports unicode, you must have the following meta tag in the '<head>' '</head>' block of your HTML file:
...
```

#### <a name="apidoc.element.draft-js.DraftEditorContents_react.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorContents_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorContents_react.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps) {
  var prevEditorState = this.props.editorState;
  var nextEditorState = nextProps.editorState;

  var prevDirectionMap = prevEditorState.getDirectionMap();
  var nextDirectionMap = nextEditorState.getDirectionMap();

  // Text direction has changed for one or more blocks. We must re-render.
  if (prevDirectionMap !== nextDirectionMap) {
    return true;
  }

  var didHaveFocus = prevEditorState.getSelection().getHasFocus();
  var nowHasFocus = nextEditorState.getSelection().getHasFocus();

  if (didHaveFocus !== nowHasFocus) {
    return true;
  }

  var nextNativeContent = nextEditorState.getNativelyRenderedContent();

  var wasComposing = prevEditorState.isInCompositionMode();
  var nowComposing = nextEditorState.isInCompositionMode();

  // If the state is unchanged or we're currently rendering a natively
  // rendered state, there's nothing new to be done.
  if (prevEditorState === nextEditorState || nextNativeContent !== null && nextEditorState.getCurrentContent() === nextNativeContent
 || wasComposing && nowComposing) {
    return false;
  }

  var prevContent = prevEditorState.getCurrentContent();
  var nextContent = nextEditorState.getCurrentContent();
  var prevDecorator = prevEditorState.getDecorator();
  var nextDecorator = nextEditorState.getDecorator();
  return wasComposing !== nowComposing || prevContent !== nextContent || prevDecorator !== nextDecorator || nextEditorState.mustForceSelection
();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorDragHandler"></a>[module draft-js.DraftEditorDragHandler](#apidoc.module.draft-js.DraftEditorDragHandler)

#### <a name="apidoc.element.draft-js.DraftEditorDragHandler.onDragEnd"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorDragHandler.</span>onDragEnd (editor)](#apidoc.element.draft-js.DraftEditorDragHandler.onDragEnd)
- description and source-code
```javascript
function onDragEnd(editor) {
  editor.exitCurrentMode();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorDragHandler.onDrop"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorDragHandler.</span>onDrop (editor, e)](#apidoc.element.draft-js.DraftEditorDragHandler.onDrop)
- description and source-code
```javascript
function onDrop(editor, e) {
  var data = new DataTransfer(e.nativeEvent.dataTransfer);

  var editorState = editor._latestEditorState;
  var dropSelection = getSelectionForEvent(e.nativeEvent, editorState);

  e.preventDefault();
  editor.exitCurrentMode();

  if (dropSelection == null) {
    return;
  }

  var files = data.getFiles();
  if (files.length > 0) {
    if (editor.props.handleDroppedFiles && isEventHandled(editor.props.handleDroppedFiles(dropSelection, files))) {
      return;
    }

    getTextContentFromFiles(files, function (fileText) {
      fileText && editor.update(insertTextAtSelection(editorState, nullthrows(dropSelection), // flow wtf
      fileText));
    });
    return;
  }

  var dragType = editor._internalDrag ? 'internal' : 'external';
  if (editor.props.handleDrop && isEventHandled(editor.props.handleDrop(dropSelection, data, dragType))) {
    return;
  }

  if (editor._internalDrag) {
    editor.update(moveText(editorState, dropSelection));
    return;
  }

  editor.update(insertTextAtSelection(editorState, dropSelection, data.getText()));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorEditHandler"></a>[module draft-js.DraftEditorEditHandler](#apidoc.module.draft-js.DraftEditorEditHandler)

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onBeforeInput"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onBeforeInput (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onBeforeInput)
- description and source-code
```javascript
function editOnBeforeInput(editor, e) {
  if (editor._pendingStateFromBeforeInput !== undefined) {
    editor.update(editor._pendingStateFromBeforeInput);
    editor._pendingStateFromBeforeInput = undefined;
  }

  var chars = e.data;

  // In some cases (ex: IE ideographic space insertion) no character data
  // is provided. There's nothing to do when this happens.
  if (!chars) {
    return;
  }

  // Allow the top-level component to handle the insertion manually. This is
  // useful when triggering interesting behaviors for a character insertion,
  // Simple examples: replacing a raw text ':)' with a smile emoji or image
  // decorator, or setting a block to be a list item after typing '- ' at the
  // start of the block.
  if (editor.props.handleBeforeInput && isEventHandled(editor.props.handleBeforeInput(chars))) {
    e.preventDefault();
    return;
  }

  // If selection is collapsed, conditionally allow native behavior. This
  // reduces re-renders and preserves spellcheck highlighting. If the selection
  // is not collapsed, we will re-render.
  var editorState = editor._latestEditorState;
  var selection = editorState.getSelection();

  if (!selection.isCollapsed()) {
    e.preventDefault();
    editor.update(replaceText(editorState, chars, editorState.getCurrentInlineStyle(), getEntityKeyForSelection(editorState.getCurrentContent
(), editorState.getSelection())));
    return;
  }

  var mayAllowNative = !isSelectionAtLeafStart(editorState);
  var newEditorState = replaceText(editorState, chars, editorState.getCurrentInlineStyle(), getEntityKeyForSelection(editorState
.getCurrentContent(), editorState.getSelection()));

  if (!mayAllowNative) {
    e.preventDefault();
    editor.update(newEditorState);
    return;
  }

  var anchorKey = selection.getAnchorKey();
  var anchorTree = editorState.getBlockTree(anchorKey);

  // Check the old and new "fingerprints" of the current block to determine
  // whether this insertion requires any addition or removal of text nodes,
  // in which case we would prevent the native character insertion.
  var originalFingerprint = BlockTree.getFingerprint(anchorTree);
  var newFingerprint = BlockTree.getFingerprint(newEditorState.getBlockTree(anchorKey));

  if (mustPreventDefaultForCharacter(chars) || originalFingerprint !== newFingerprint || nullthrows(newEditorState.getDirectionMap
()).get(anchorKey) !== nullthrows(editorState.getDirectionMap()).get(anchorKey)) {
    e.preventDefault();
    editor.update(newEditorState);
  } else {
    newEditorState = EditorState.set(newEditorState, {
      nativelyRenderedContent: newEditorState.getCurrentContent()
    });
    // The native event is allowed to occur. To allow user onChange handlers to
    // change the inserted text, we wait until the text is actually inserted
    // before we actually update our state. That way when we rerender, the text
    // we see in the DOM will already have been inserted properly.
    editor._pendingStateFromBeforeInput = newEditorState;
    setImmediate(function () {
      if (editor._pendingStateFromBeforeInput !== undefined) {
        editor.update(editor._pendingStateFromBeforeInput);
        editor._pendingStateFromBeforeInput = undefined;
      }
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onBlur"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onBlur (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onBlur)
- description and source-code
```javascript
function editOnBlur(editor, e) {
  // Webkit has a bug in which blurring a contenteditable by clicking on
  // other active elements will trigger the 'blur' event but will not remove
  // the DOM selection from the contenteditable. We therefore force the
  // issue to be certain, checking whether the active element is 'body'
  // to force it when blurring occurs within the window (as opposed to
  // clicking to another tab or window).
  if (isWebKit && getActiveElement() === document.body) {
    global.getSelection().removeAllRanges();
  }

  var editorState = editor._latestEditorState;
  var currentSelection = editorState.getSelection();
  if (!currentSelection.getHasFocus()) {
    return;
  }

  var selection = currentSelection.set('hasFocus', false);
  editor.props.onBlur && editor.props.onBlur(e);
  editor.update(EditorState.acceptSelection(editorState, selection));
}
```
- example usage
```shell
...
  var editorState = editor._latestEditorState;
  var currentSelection = editorState.getSelection();
  if (!currentSelection.getHasFocus()) {
    return;
  }

  var selection = currentSelection.set('hasFocus', false);
  editor.props.onBlur && editor.props.onBlur(e);
  editor.update(EditorState.acceptSelection(editorState, selection));
}

module.exports = editOnBlur;
...
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onCompositionStart"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onCompositionStart (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onCompositionStart)
- description and source-code
```javascript
function editOnCompositionStart(editor, e) {
  editor.setMode('composite');
  editor.update(EditorState.set(editor._latestEditorState, { inCompositionMode: true }));
  // Allow composition handler to interpret the compositionstart event
  editor._onCompositionStart(e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onCopy"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onCopy (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onCopy)
- description and source-code
```javascript
function editOnCopy(editor, e) {
  var editorState = editor._latestEditorState;
  var selection = editorState.getSelection();

  // No selection, so there's nothing to copy.
  if (selection.isCollapsed()) {
    e.preventDefault();
    return;
  }

  editor.setClipboard(getFragmentFromSelection(editor._latestEditorState));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onCut"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onCut (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onCut)
- description and source-code
```javascript
function editOnCut(editor, e) {
  var editorState = editor._latestEditorState;
  var selection = editorState.getSelection();

  // No selection, so there's nothing to cut.
  if (selection.isCollapsed()) {
    e.preventDefault();
    return;
  }

  // Track the current scroll position so that it can be forced back in place
  // after the editor regains control of the DOM.
  var scrollParent = Style.getScrollParent(e.target);

  var _getScrollPosition = getScrollPosition(scrollParent);

  var x = _getScrollPosition.x;
  var y = _getScrollPosition.y;


  var fragment = getFragmentFromSelection(editorState);
  editor.setClipboard(fragment);

  // Set 'cut' mode to disable all event handling temporarily.
  editor.setMode('cut');

  // Let native 'cut' behavior occur, then recover control.
  setTimeout(function () {
    editor.restoreEditorDOM({ x: x, y: y });
    editor.exitCurrentMode();
    editor.update(removeFragment(editorState));
  }, 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onDragOver"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onDragOver (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onDragOver)
- description and source-code
```javascript
function editOnDragOver(editor, e) {
  editor._internalDrag = false;
  editor.setMode('drag');
  e.preventDefault();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onDragStart"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onDragStart (editor)](#apidoc.element.draft-js.DraftEditorEditHandler.onDragStart)
- description and source-code
```javascript
function editOnDragStart(editor) {
  editor._internalDrag = true;
  editor.setMode('drag');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onFocus"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onFocus (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onFocus)
- description and source-code
```javascript
function editOnFocus(editor, e) {
  var editorState = editor._latestEditorState;
  var currentSelection = editorState.getSelection();
  if (currentSelection.getHasFocus()) {
    return;
  }

  var selection = currentSelection.set('hasFocus', true);
  editor.props.onFocus && editor.props.onFocus(e);

  // When the tab containing this text editor is hidden and the user does a
  // find-in-page in a _different_ tab, Chrome on Mac likes to forget what the
  // selection was right after sending this focus event and (if you let it)
  // moves the cursor back to the beginning of the editor, so we force the
  // selection here instead of simply accepting it in order to preserve the
  // old cursor position. See https://crbug.com/540004.
  editor.update(EditorState.forceSelection(editorState, selection));
}
```
- example usage
```shell
...
var editorState = editor._latestEditorState;
var currentSelection = editorState.getSelection();
if (currentSelection.getHasFocus()) {
  return;
}

var selection = currentSelection.set('hasFocus', true);
editor.props.onFocus && editor.props.onFocus(e);

// When the tab containing this text editor is hidden and the user does a
// find-in-page in a _different_ tab, Chrome on Mac likes to forget what the
// selection was right after sending this focus event and (if you let it)
// moves the cursor back to the beginning of the editor, so we force the
// selection here instead of simply accepting it in order to preserve the
// old cursor position. See https://crbug.com/540004.
...
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onInput"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onInput (editor)](#apidoc.element.draft-js.DraftEditorEditHandler.onInput)
- description and source-code
```javascript
function editOnInput(editor) {
  if (editor._pendingStateFromBeforeInput !== undefined) {
    editor.update(editor._pendingStateFromBeforeInput);
    editor._pendingStateFromBeforeInput = undefined;
  }

  var domSelection = global.getSelection();

  var anchorNode = domSelection.anchorNode;
  var isCollapsed = domSelection.isCollapsed;

  if (anchorNode.nodeType !== Node.TEXT_NODE) {
    return;
  }

  var domText = anchorNode.textContent;
  var editorState = editor._latestEditorState;
  var offsetKey = nullthrows(findAncestorOffsetKey(anchorNode));

  var _DraftOffsetKey$decod = DraftOffsetKey.decode(offsetKey);

  var blockKey = _DraftOffsetKey$decod.blockKey;
  var decoratorKey = _DraftOffsetKey$decod.decoratorKey;
  var leafKey = _DraftOffsetKey$decod.leafKey;

  var _editorState$getBlock = editorState.getBlockTree(blockKey).getIn([decoratorKey, 'leaves', leafKey]);

  var start = _editorState$getBlock.start;
  var end = _editorState$getBlock.end;


  var content = editorState.getCurrentContent();
  var block = content.getBlockForKey(blockKey);
  var modelText = block.getText().slice(start, end);

  // Special-case soft newlines here. If the DOM text ends in a soft newline,
  // we will have manually inserted an extra soft newline in DraftEditorLeaf.
  // We want to remove this extra newline for the purpose of our comparison
  // of DOM and model text.
  if (domText.endsWith(DOUBLE_NEWLINE)) {
    domText = domText.slice(0, -1);
  }

  // No change -- the DOM is up to date. Nothing to do here.
  if (domText === modelText) {
    return;
  }

  var selection = editorState.getSelection();

  // We'll replace the entire leaf with the text content of the target.
  var targetRange = selection.merge({
    anchorOffset: start,
    focusOffset: end,
    isBackward: false
  });

  var entityKey = block.getEntityAt(start);
  var entity = entityKey && content.getEntity(entityKey);
  var entityType = entity && entity.getMutability();
  var preserveEntity = entityType === 'MUTABLE';

  // Immutable or segmented entities cannot properly be handled by the
  // default browser undo, so we have to use a different change type to
  // force using our internal undo method instead of falling through to the
  // native browser undo.
  var changeType = preserveEntity ? 'spellcheck-change' : 'apply-entity';

  var newContent = DraftModifier.replaceText(content, targetRange, domText, block.getInlineStyleAt(start), preserveEntity ? block
.getEntityAt(start) : null);

  var anchorOffset, focusOffset, startOffset, endOffset;

  if (isGecko) {
    // Firefox selection does not change while the context menu is open, so
    // we preserve the anchor and focus values of the DOM selection.
    anchorOffset = domSelection.anchorOffset;
    focusOffset = domSelection.focusOffset;
    startOffset = start + Math.min(anchorOffset, focusOffset);
    endOffset = startOffset + Math.abs(anchorOffset - focusOffset);
    anchorOffset = startOffset;
    focusOffset = endOffset;
  } else {
    // Browsers other than Firefox may adjust DOM selection while the context
    // menu is open, and Safari autocorrect is prone to providing an inaccurate
    // DOM selection. Don't trust it. Instead, use our existing SelectionState
    // and adjust it based on the number of characters changed during the
    // mutation.
    var charDelta = domText.length - modelText.length;
    startOffset = selection.getStartOffset();
    endOffset = selection.getEndOffset();

    anchorOffset = isCollapsed ? endOffset + charDelta : startOffset;
    focusOffset = endOffset + charDelta;
  }

  // Segmented entities are completely or partially removed when their
  // text content changes. For this case we do not want any text to be selected
  // after the change, so we are not merging the selection.
  var contentWithAdjustedDOMSelection = newContent.merge({
    selectionBefore: content.getSelectionAfter(),
    selectionAfter: selection.merge({ anchorOffset: anchorOffset, focusOffset: focusOffset })
  });

  editor.update(EditorState.push(editorState, contentWithAdjustedDOMSelection, chang ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onKeyDown"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onKeyDown (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onKeyDown)
- description and source-code
```javascript
function editOnKeyDown(editor, e) {
  var keyCode = e.which;
  var editorState = editor._latestEditorState;

  switch (keyCode) {
    case Keys.RETURN:
      e.preventDefault();
      // The top-level component may manually handle newline insertion. If
      // no special handling is performed, fall through to command handling.
      if (editor.props.handleReturn && isEventHandled(editor.props.handleReturn(e))) {
        return;
      }
      break;
    case Keys.ESC:
      e.preventDefault();
      editor.props.onEscape && editor.props.onEscape(e);
      return;
    case Keys.TAB:
      editor.props.onTab && editor.props.onTab(e);
      return;
    case Keys.UP:
      editor.props.onUpArrow && editor.props.onUpArrow(e);
      return;
    case Keys.DOWN:
      editor.props.onDownArrow && editor.props.onDownArrow(e);
      return;
    case Keys.SPACE:
      // Handling for OSX where option + space scrolls.
      if (isChrome && isOptionKeyCommand(e)) {
        e.preventDefault();
        // Insert a nbsp into the editor.
        var contentState = DraftModifier.replaceText(editorState.getCurrentContent(), editorState.getSelection(), '\xA0');
        editor.update(EditorState.push(editorState, contentState, 'insert-characters'));
        return;
      }
  }

  var command = editor.props.keyBindingFn(e);

  // If no command is specified, allow keydown event to continue.
  if (!command) {
    return;
  }

  if (command === 'undo') {
    // Since undo requires some special updating behavior to keep the editor
    // in sync, handle it separately.
    keyCommandUndo(e, editorState, editor.update);
    return;
  }

  // At this point, we know that we're handling a command of some kind, so
  // we don't want to insert a character following the keydown.
  e.preventDefault();

  // Allow components higher up the tree to handle the command first.
  if (editor.props.handleKeyCommand && isEventHandled(editor.props.handleKeyCommand(command))) {
    return;
  }

  var newState = onKeyCommand(command, editorState);
  if (newState !== editorState) {
    editor.update(newState);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onPaste"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onPaste (editor, e)](#apidoc.element.draft-js.DraftEditorEditHandler.onPaste)
- description and source-code
```javascript
function editOnPaste(editor, e) {
  e.preventDefault();
  var data = new DataTransfer(e.clipboardData);

  // Get files, unless this is likely to be a string the user wants inline.
  if (!data.isRichText()) {
    var files = data.getFiles();
    var defaultFileText = data.getText();
    if (files.length > 0) {
      // Allow customized paste handling for images, etc. Otherwise, fall
      // through to insert text contents into the editor.
      if (editor.props.handlePastedFiles && isEventHandled(editor.props.handlePastedFiles(files))) {
        return;
      }

      getTextContentFromFiles(files, function ( /*string*/fileText) {
        fileText = fileText || defaultFileText;
        if (!fileText) {
          return;
        }

        var editorState = editor._latestEditorState;
        var blocks = splitTextIntoTextBlocks(fileText);
        var character = CharacterMetadata.create({
          style: editorState.getCurrentInlineStyle(),
          entity: getEntityKeyForSelection(editorState.getCurrentContent(), editorState.getSelection())
        });

        var text = DraftPasteProcessor.processText(blocks, character);
        var fragment = BlockMapBuilder.createFromArray(text);

        var withInsertedText = DraftModifier.replaceWithFragment(editorState.getCurrentContent(), editorState.getSelection(), fragment
);

        editor.update(EditorState.push(editorState, withInsertedText, 'insert-fragment'));
      });

      return;
    }
  }

  var textBlocks = [];
  var text = data.getText();
  var html = data.getHTML();

  if (editor.props.handlePastedText && isEventHandled(editor.props.handlePastedText(text, html))) {
    return;
  }

  if (text) {
    textBlocks = splitTextIntoTextBlocks(text);
  }

  if (!editor.props.stripPastedStyles) {
    // If the text from the paste event is rich content that matches what we
    // already have on the internal clipboard, assume that we should just use
    // the clipboard fragment for the paste. This will allow us to preserve
    // styling and entities, if any are present. Note that newlines are
    // stripped during comparison -- this is because copy/paste within the
    // editor in Firefox and IE will not include empty lines. The resulting
    // paste will preserve the newlines correctly.
    var internalClipboard = editor.getClipboard();
    if (data.isRichText() && internalClipboard) {
      if (
      // If the editorKey is present in the pasted HTML, it should be safe to
      // assume this is an internal paste.
      html.indexOf(editor.getEditorKey()) !== -1 ||
      // The copy may have been made within a single block, in which case the
      // editor key won't be part of the paste. In this case, just check
      // whether the pasted text matches the internal clipboard.
      textBlocks.length === 1 && internalClipboard.size === 1 && internalClipboard.first().getText() === text) {
        editor.update(insertFragment(editor._latestEditorState, internalClipboard));
        return;
      }
    } else if (internalClipboard && data.types.includes('com.apple.webarchive') && !data.types.includes('text/html') && areTextBlocksAndClipboardEqual
(textBlocks, internalClipboard)) {
      // Safari does not properly store text/html in some cases.
      // Use the internalClipboard if present and equal to what is on
      // the clipboard. See https://bugs.webkit.org/show_bug.cgi?id=19893.
      editor.update(insertFragment(editor._latestEditorState, internalClipboard));
      return;
    }

    // If there is html paste data, try to parse that.
    if (html) {
      var htmlFragment = DraftPasteProcessor.processHTML(html, editor.props.blockRenderMap);
      if (htmlFragment) {
        var contentBlocks = htmlFragment.contentBlocks;
        var entityMap = htmlFragment.entityMap;

        if (contentBlocks) {
          var htmlMap = BlockMapBuilder.createFromArray(contentBlocks);
          editor.update(insertFragment(editor._latestEditorState, htmlMap, entityMap));
          return;
        }
      }
    }

    // Otherwise, create a new fragment from our pasted text. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorEditHandler.onSelect"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorEditHandler.</span>onSelect (editor)](#apidoc.element.draft-js.DraftEditorEditHandler.onSelect)
- description and source-code
```javascript
function editOnSelect(editor) {
  if (editor._blockSelectEvents || editor._latestEditorState !== editor.props.editorState) {
    return;
  }

  var editorState = editor.props.editorState;
  var documentSelection = getDraftEditorSelection(editorState, ReactDOM.findDOMNode(editor.refs.editorContainer).firstChild);
  var updatedSelectionState = documentSelection.selectionState;

  if (updatedSelectionState !== editorState.getSelection()) {
    if (documentSelection.needsRecovery) {
      editorState = EditorState.forceSelection(editorState, updatedSelectionState);
    } else {
      editorState = EditorState.acceptSelection(editorState, updatedSelectionState);
    }
    editor.update(editorState);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorLeaf_react"></a>[module draft-js.DraftEditorLeaf_react](#apidoc.module.draft-js.DraftEditorLeaf_react)

#### <a name="apidoc.element.draft-js.DraftEditorLeaf_react.DraftEditorLeaf_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorLeaf_react ()](#apidoc.element.draft-js.DraftEditorLeaf_react.DraftEditorLeaf_react)
- description and source-code
```javascript
function DraftEditorLeaf() {
  _classCallCheck(this, DraftEditorLeaf);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorLeaf_react.prototype"></a>[module draft-js.DraftEditorLeaf_react.prototype](#apidoc.module.draft-js.DraftEditorLeaf_react.prototype)

#### <a name="apidoc.element.draft-js.DraftEditorLeaf_react.prototype._setSelection"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>_setSelection ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype._setSelection)
- description and source-code
```javascript
function _setSelection() {
  var selection = this.props.selection;

  // If selection state is irrelevant to the parent block, no-op.

  if (selection == null || !selection.getHasFocus()) {
    return;
  }

  var _props = this.props;
  var blockKey = _props.blockKey;
  var start = _props.start;
  var text = _props.text;

  var end = start + text.length;
  if (!selection.hasEdgeWithin(blockKey, start, end)) {
    return;
  }

  // Determine the appropriate target node for selection. If the child
  // is not a text node, it is a <br /> spacer. In this case, use the
  // <span> itself as the selection target.
  var node = ReactDOM.findDOMNode(this);
  var child = node.firstChild;
  var targetNode = void 0;

  if (child.nodeType === Node.TEXT_NODE) {
    targetNode = child;
  } else if (child.tagName === 'BR') {
    targetNode = node;
  } else {
    targetNode = child.firstChild;
  }

  setDraftEditorSelection(selection, targetNode, blockKey, start, end);
}
```
- example usage
```shell
...
};

DraftEditorLeaf.prototype.shouldComponentUpdate = function shouldComponentUpdate(nextProps) {
  return ReactDOM.findDOMNode(this.refs.leaf).textContent !== nextProps.text || nextProps.styleSet !== this.props.styleSet || nextProps
.forceSelection;
};

DraftEditorLeaf.prototype.componentDidUpdate = function componentDidUpdate() {
  this._setSelection();
};

DraftEditorLeaf.prototype.componentDidMount = function componentDidMount() {
  this._setSelection();
};

DraftEditorLeaf.prototype.render = function render() {
...
```

#### <a name="apidoc.element.draft-js.DraftEditorLeaf_react.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>componentDidMount ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  this._setSelection();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorLeaf_react.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>componentDidUpdate ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
  this._setSelection();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorLeaf_react.prototype.render"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.render)
- description and source-code
```javascript
function render() {
  var text = this.props.text;

  // If the leaf is at the end of its block and ends in a soft newline, append
  // an extra line feed character. Browsers collapse trailing newline
  // characters, which leaves the cursor in the wrong place after a
  // shift+enter. The extra character repairs this.

  if (text.endsWith('\n') && this.props.isLast) {
    text += '\n';
  }

  var _props2 = this.props;
  var customStyleMap = _props2.customStyleMap;
  var customStyleFn = _props2.customStyleFn;
  var offsetKey = _props2.offsetKey;
  var styleSet = _props2.styleSet;

  var styleObj = styleSet.reduce(function (map, styleName) {
    var mergedStyles = {};
    var style = customStyleMap[styleName];

    if (style !== undefined && map.textDecoration !== style.textDecoration) {
      // .trim() is necessary for IE9/10/11 and Edge
      mergedStyles.textDecoration = [map.textDecoration, style.textDecoration].join(' ').trim();
    }

    return _assign(map, style, mergedStyles);
  }, {});

  if (customStyleFn) {
    var newStyles = customStyleFn(styleSet);
    styleObj = _assign(styleObj, newStyles);
  }

  return React.createElement(
    'span',
    {
      'data-offset-key': offsetKey,
      ref: 'leaf',
      style: styleObj },
    React.createElement(
      DraftEditorTextNode,
      null,
      text
    )
  );
}
```
- example usage
```shell
...
  render() {
    return (
        <Editor editorState={this.state.editorState} onChange={this.onChange} />
    );
  }
}

ReactDOM.render(
  <MyEditor />,
  document.getElementById('container')
);
'''

Because Draft.js supports unicode, you must have the following meta tag in the '<head>' '</head>' block of your HTML file:
...
```

#### <a name="apidoc.element.draft-js.DraftEditorLeaf_react.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorLeaf_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorLeaf_react.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps) {
  return ReactDOM.findDOMNode(this.refs.leaf).textContent !== nextProps.text || nextProps.styleSet !== this.props.styleSet || nextProps
.forceSelection;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorPlaceholder_react"></a>[module draft-js.DraftEditorPlaceholder_react](#apidoc.module.draft-js.DraftEditorPlaceholder_react)

#### <a name="apidoc.element.draft-js.DraftEditorPlaceholder_react.DraftEditorPlaceholder_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorPlaceholder_react ()](#apidoc.element.draft-js.DraftEditorPlaceholder_react.DraftEditorPlaceholder_react)
- description and source-code
```javascript
function DraftEditorPlaceholder() {
  _classCallCheck(this, DraftEditorPlaceholder);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorPlaceholder_react.prototype"></a>[module draft-js.DraftEditorPlaceholder_react.prototype](#apidoc.module.draft-js.DraftEditorPlaceholder_react.prototype)

#### <a name="apidoc.element.draft-js.DraftEditorPlaceholder_react.prototype.render"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorPlaceholder_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorPlaceholder_react.prototype.render)
- description and source-code
```javascript
function render() {
  var hasFocus = this.props.editorState.getSelection().getHasFocus();

  var className = cx({
    'public/DraftEditorPlaceholder/root': true,
    'public/DraftEditorPlaceholder/hasFocus': hasFocus
  });

  return React.createElement(
    'div',
    { className: className },
    React.createElement(
      'div',
      {
        className: cx('public/DraftEditorPlaceholder/inner'),
        id: this.props.accessibilityID },
      this.props.text
    )
  );
}
```
- example usage
```shell
...
  render() {
    return (
        <Editor editorState={this.state.editorState} onChange={this.onChange} />
    );
  }
}

ReactDOM.render(
  <MyEditor />,
  document.getElementById('container')
);
'''

Because Draft.js supports unicode, you must have the following meta tag in the '<head>' '</head>' block of your HTML file:
...
```

#### <a name="apidoc.element.draft-js.DraftEditorPlaceholder_react.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorPlaceholder_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorPlaceholder_react.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps) {
  return this.props.text !== nextProps.text || this.props.editorState.getSelection().getHasFocus() !== nextProps.editorState.getSelection
().getHasFocus();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorTextNode_react"></a>[module draft-js.DraftEditorTextNode_react](#apidoc.module.draft-js.DraftEditorTextNode_react)

#### <a name="apidoc.element.draft-js.DraftEditorTextNode_react.DraftEditorTextNode_react"></a>[function <span class="apidocSignatureSpan">draft-js.</span>DraftEditorTextNode_react (props)](#apidoc.element.draft-js.DraftEditorTextNode_react.DraftEditorTextNode_react)
- description and source-code
```javascript
function DraftEditorTextNode(props) {
  _classCallCheck(this, DraftEditorTextNode);

  var _this = _possibleConstructorReturn(this, _React$Component.call(this, props));

  _this._forceFlag = false;
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEditorTextNode_react.prototype"></a>[module draft-js.DraftEditorTextNode_react.prototype](#apidoc.module.draft-js.DraftEditorTextNode_react.prototype)

#### <a name="apidoc.element.draft-js.DraftEditorTextNode_react.prototype.componentWillUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorTextNode_react.prototype.</span>componentWillUpdate ()](#apidoc.element.draft-js.DraftEditorTextNode_react.prototype.componentWillUpdate)
- description and source-code
```javascript
function componentWillUpdate() {
  // By flipping this flag, we also keep flipping keys which forces
  // React to remount this node every time it rerenders.
  this._forceFlag = !this._forceFlag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.DraftEditorTextNode_react.prototype.render"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorTextNode_react.prototype.</span>render ()](#apidoc.element.draft-js.DraftEditorTextNode_react.prototype.render)
- description and source-code
```javascript
function render() {
  if (this.props.children === '') {
    return this._forceFlag ? NEWLINE_A : NEWLINE_B;
  }
  return React.createElement(
    'span',
    { key: this._forceFlag ? 'A' : 'B', 'data-text': 'true' },
    this.props.children
  );
}
```
- example usage
```shell
...
  render() {
    return (
        <Editor editorState={this.state.editorState} onChange={this.onChange} />
    );
  }
}

ReactDOM.render(
  <MyEditor />,
  document.getElementById('container')
);
'''

Because Draft.js supports unicode, you must have the following meta tag in the '<head>' '</head>' block of your HTML file:
...
```

#### <a name="apidoc.element.draft-js.DraftEditorTextNode_react.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEditorTextNode_react.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.DraftEditorTextNode_react.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps) {
  var node = ReactDOM.findDOMNode(this);
  var shouldBeNewline = nextProps.children === '';
  if (shouldBeNewline) {
    return !isNewline(node);
  }
  return node.textContent !== nextProps.children;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.DraftEntitySegments"></a>[module draft-js.DraftEntitySegments](#apidoc.module.draft-js.DraftEntitySegments)

#### <a name="apidoc.element.draft-js.DraftEntitySegments.getRemovalRange"></a>[function <span class="apidocSignatureSpan">draft-js.DraftEntitySegments.</span>getRemovalRange (selectionStart, selectionEnd, text, entityStart, direction)](#apidoc.element.draft-js.DraftEntitySegments.getRemovalRange)
- description and source-code
```javascript
function getRemovalRange(selectionStart, selectionEnd, text, entityStart, direction) {
  var segments = text.split(' ');
  segments = segments.map(function ( /*string*/segment, /*number*/ii) {
    if (direction === 'forward') {
      if (ii > 0) {
        return ' ' + segment;
      }
    } else if (ii < segments.length - 1) {
      return segment + ' ';
    }
    return segment;
  });

  var segmentStart = entityStart;
  var segmentEnd;
  var segment;
  var removalStart = null;
  var removalEnd = null;

  for (var jj = 0; jj < segments.length; jj++) {
    segment = segments[jj];
    segmentEnd = segmentStart + segment.length;

    // Our selection overlaps this segment.
    if (selectionStart < segmentEnd && segmentStart < selectionEnd) {
      if (removalStart !== null) {
        removalEnd = segmentEnd;
      } else {
        removalStart = segmentStart;
        removalEnd = segmentEnd;
      }
    } else if (removalStart !== null) {
      break;
    }

    segmentStart = segmentEnd;
  }

  var entityEnd = entityStart + text.length;
  var atStart = removalStart === entityStart;
  var atEnd = removalEnd === entityEnd;

  if (!atStart && atEnd || atStart && !atEnd) {
    if (direction === 'forward') {
      if (removalEnd !== entityEnd) {
        removalEnd++;
      }
    } else if (removalStart !== entityStart) {
      removalStart--;
    }
  }

  return {
    start: removalStart,
    end: removalEnd
  };
}
```
- example usage
```shell
...
      focusOffset: entityRange.end,
      isBackward: false
    });
  }

  // For 'SEGMENTED' entity types, determine the appropriate segment to
  // remove.
  var removalRange = DraftEntitySegments.getRemovalRange(start, end, block.getText().slice(entityRange.start, entityRange.end),
entityRange.start, direction);

  return selectionState.merge({
    anchorOffset: removalRange.start,
    focusOffset: removalRange.end,
    isBackward: false
  });
}
...
```



# <a name="apidoc.module.draft-js.DraftOffsetKey"></a>[module draft-js.DraftOffsetKey](#apidoc.module.draft-js.DraftOffsetKey)

#### <a name="apidoc.element.draft-js.DraftOffsetKey.decode"></a>[function <span class="apidocSignatureSpan">draft-js.DraftOffsetKey.</span>decode (offsetKey)](#apidoc.element.draft-js.DraftOffsetKey.decode)
- description and source-code
```javascript
function decode(offsetKey) {
  var _offsetKey$split = offsetKey.split(KEY_DELIMITER);

  var blockKey = _offsetKey$split[0];
  var decoratorKey = _offsetKey$split[1];
  var leafKey = _offsetKey$split[2];

  return {
    blockKey: blockKey,
    decoratorKey: parseInt(decoratorKey, 10),
    leafKey: parseInt(leafKey, 10)
  };
}
```
- example usage
```shell
...
  return;
}

var domText = anchorNode.textContent;
var editorState = editor._latestEditorState;
var offsetKey = nullthrows(findAncestorOffsetKey(anchorNode));

var _DraftOffsetKey$decod = DraftOffsetKey.decode(offsetKey);

var blockKey = _DraftOffsetKey$decod.blockKey;
var decoratorKey = _DraftOffsetKey$decod.decoratorKey;
var leafKey = _DraftOffsetKey$decod.leafKey;

var _editorState$getBlock = editorState.getBlockTree(blockKey).getIn([decoratorKey, 'leaves', leafKey]);
...
```

#### <a name="apidoc.element.draft-js.DraftOffsetKey.encode"></a>[function <span class="apidocSignatureSpan">draft-js.DraftOffsetKey.</span>encode (blockKey, decoratorKey, leafKey)](#apidoc.element.draft-js.DraftOffsetKey.encode)
- description and source-code
```javascript
function encode(blockKey, decoratorKey, leafKey) {
  return blockKey + KEY_DELIMITER + decoratorKey + KEY_DELIMITER + leafKey;
}
```
- example usage
```shell
...
if (customRenderer) {
  CustomComponent = customRenderer.component;
  customProps = customRenderer.props;
  customEditable = customRenderer.editable;
}

var direction = directionMap.get(key);
var offsetKey = DraftOffsetKey.encode(key, 0, 0);
var componentProps = {
  contentState: content,
  block: _block,
  blockProps: customProps,
  customStyleMap: customStyleMap,
  customStyleFn: customStyleFn,
  decorator: decorator,
...
```



# <a name="apidoc.module.draft-js.DraftPasteProcessor"></a>[module draft-js.DraftPasteProcessor](#apidoc.module.draft-js.DraftPasteProcessor)

#### <a name="apidoc.element.draft-js.DraftPasteProcessor.processHTML"></a>[function <span class="apidocSignatureSpan">draft-js.DraftPasteProcessor.</span>processHTML (html, blockRenderMap)](#apidoc.element.draft-js.DraftPasteProcessor.processHTML)
- description and source-code
```javascript
function processHTML(html, blockRenderMap) {
  return convertFromHTMLtoContentBlocks(html, getSafeBodyFromHTML, blockRenderMap);
}
```
- example usage
```shell
...
      // the clipboard. See https://bugs.webkit.org/show_bug.cgi?id=19893.
      editor.update(insertFragment(editor._latestEditorState, internalClipboard));
      return;
    }

    // If there is html paste data, try to parse that.
    if (html) {
      var htmlFragment = DraftPasteProcessor.processHTML(html, editor.props.blockRenderMap);
      if (htmlFragment) {
var contentBlocks = htmlFragment.contentBlocks;
var entityMap = htmlFragment.entityMap;

if (contentBlocks) {
  var htmlMap = BlockMapBuilder.createFromArray(contentBlocks);
  editor.update(insertFragment(editor._latestEditorState, htmlMap, entityMap));
...
```

#### <a name="apidoc.element.draft-js.DraftPasteProcessor.processText"></a>[function <span class="apidocSignatureSpan">draft-js.DraftPasteProcessor.</span>processText (textBlocks, character)](#apidoc.element.draft-js.DraftPasteProcessor.processText)
- description and source-code
```javascript
function processText(textBlocks, character) {
  return textBlocks.map(function (textLine) {
    textLine = sanitizeDraftText(textLine);
    return new ContentBlock({
      key: generateRandomKey(),
      type: 'unstyled',
      text: textLine,
      characterList: List(Repeat(character, textLine.length))
    });
  });
}
```
- example usage
```shell
...
  var editorState = editor._latestEditorState;
  var blocks = splitTextIntoTextBlocks(fileText);
  var character = CharacterMetadata.create({
    style: editorState.getCurrentInlineStyle(),
    entity: getEntityKeyForSelection(editorState.getCurrentContent(), editorState.getSelection())
  });

  var text = DraftPasteProcessor.processText(blocks, character);
  var fragment = BlockMapBuilder.createFromArray(text);

  var withInsertedText = DraftModifier.replaceWithFragment(editorState.getCurrentContent(), editorState.getSelection(), fragment
);

  editor.update(EditorState.push(editorState, withInsertedText, 'insert-fragment'));
});
...
```



# <a name="apidoc.module.draft-js.DraftRemovableWord"></a>[module draft-js.DraftRemovableWord](#apidoc.module.draft-js.DraftRemovableWord)

#### <a name="apidoc.element.draft-js.DraftRemovableWord.getBackward"></a>[function <span class="apidocSignatureSpan">draft-js.DraftRemovableWord.</span>getBackward (text)](#apidoc.element.draft-js.DraftRemovableWord.getBackward)
- description and source-code
```javascript
function getBackward(text) {
  return getRemovableWord(text, true);
}
```
- example usage
```shell
...
  // If there are no words before the cursor, remove the preceding newline.
  if (offset === 0) {
    return moveSelectionBackward(strategyState, 1);
  }
  var key = selection.getStartKey();
  var content = strategyState.getCurrentContent();
  var text = content.getBlockForKey(key).getText().slice(0, offset);
  var toRemove = DraftRemovableWord.getBackward(text);
  return moveSelectionBackward(strategyState, toRemove.length || 1);
}, 'backward');

if (afterRemoval === editorState.getCurrentContent()) {
  return editorState;
}
...
```

#### <a name="apidoc.element.draft-js.DraftRemovableWord.getForward"></a>[function <span class="apidocSignatureSpan">draft-js.DraftRemovableWord.</span>getForward (text)](#apidoc.element.draft-js.DraftRemovableWord.getForward)
- description and source-code
```javascript
function getForward(text) {
  return getRemovableWord(text, false);
}
```
- example usage
```shell
...
function keyCommandDeleteWord(editorState) {
var afterRemoval = removeTextWithStrategy(editorState, function (strategyState) {
  var selection = strategyState.getSelection();
  var offset = selection.getStartOffset();
  var key = selection.getStartKey();
  var content = strategyState.getCurrentContent();
  var text = content.getBlockForKey(key).getText().slice(offset);
  var toRemove = DraftRemovableWord.getForward(text);

  // If there are no words in front of the cursor, remove the newline.
  return moveSelectionForward(strategyState, toRemove.length || 1);
}, 'forward');

if (afterRemoval === editorState.getCurrentContent()) {
  return editorState;
...
```



# <a name="apidoc.module.draft-js.DraftStringKey"></a>[module draft-js.DraftStringKey](#apidoc.module.draft-js.DraftStringKey)

#### <a name="apidoc.element.draft-js.DraftStringKey.stringify"></a>[function <span class="apidocSignatureSpan">draft-js.DraftStringKey.</span>stringify (key)](#apidoc.element.draft-js.DraftStringKey.stringify)
- description and source-code
```javascript
function stringify(key) {
  return '_' + String(key);
}
```
- example usage
```shell
...
  var rawBlocks = [];

  contentState.getBlockMap().forEach(function (block, blockKey) {
block.findEntityRanges(function (character) {
  return character.getEntity() !== null;
}, function (start) {
  // Stringify to maintain order of otherwise numeric keys.
  var stringifiedEntityKey = DraftStringKey.stringify(block.getEntityAt(start));
  if (!entityStorageMap.hasOwnProperty(stringifiedEntityKey)) {
    entityStorageMap[stringifiedEntityKey] = '' + entityStorageKey++;
  }
});

rawBlocks.push({
  key: blockKey,
...
```

#### <a name="apidoc.element.draft-js.DraftStringKey.unstringify"></a>[function <span class="apidocSignatureSpan">draft-js.DraftStringKey.</span>unstringify (key)](#apidoc.element.draft-js.DraftStringKey.unstringify)
- description and source-code
```javascript
function unstringify(key) {
  return key.slice(1);
}
```
- example usage
```shell
...
});

// Flip storage map so that our storage keys map to global
// DraftEntity keys.
var entityKeys = Object.keys(entityStorageMap);
var flippedStorageMap = {};
entityKeys.forEach(function (key, jj) {
  var entity = contentState.getEntity(DraftStringKey.unstringify(key));
  flippedStorageMap[jj] = {
    type: entity.getType(),
    mutability: entity.getMutability(),
    data: entity.getData()
  };
});
...
```



# <a name="apidoc.module.draft-js.Editor"></a>[module draft-js.Editor](#apidoc.module.draft-js.Editor)

#### <a name="apidoc.element.draft-js.Editor.Editor"></a>[function <span class="apidocSignatureSpan">draft-js.</span>Editor (props)](#apidoc.element.draft-js.Editor.Editor)
- description and source-code
```javascript
function DraftEditor(props) {
  _classCallCheck(this, DraftEditor);

  var _this = _possibleConstructorReturn(this, _React$Component.call(this, props));

  _this._blockSelectEvents = false;
  _this._clipboard = null;
  _this._handler = null;
  _this._dragCount = 0;
  _this._editorKey = generateRandomKey();
  _this._placeholderAccessibilityID = 'placeholder-' + _this._editorKey;
  _this._latestEditorState = props.editorState;

  _this._onBeforeInput = _this._buildHandler('onBeforeInput');
  _this._onBlur = _this._buildHandler('onBlur');
  _this._onCharacterData = _this._buildHandler('onCharacterData');
  _this._onCompositionEnd = _this._buildHandler('onCompositionEnd');
  _this._onCompositionStart = _this._buildHandler('onCompositionStart');
  _this._onCopy = _this._buildHandler('onCopy');
  _this._onCut = _this._buildHandler('onCut');
  _this._onDragEnd = _this._buildHandler('onDragEnd');
  _this._onDragOver = _this._buildHandler('onDragOver');
  _this._onDragStart = _this._buildHandler('onDragStart');
  _this._onDrop = _this._buildHandler('onDrop');
  _this._onInput = _this._buildHandler('onInput');
  _this._onFocus = _this._buildHandler('onFocus');
  _this._onKeyDown = _this._buildHandler('onKeyDown');
  _this._onKeyPress = _this._buildHandler('onKeyPress');
  _this._onKeyUp = _this._buildHandler('onKeyUp');
  _this._onMouseDown = _this._buildHandler('onMouseDown');
  _this._onMouseUp = _this._buildHandler('onMouseUp');
  _this._onPaste = _this._buildHandler('onPaste');
  _this._onSelect = _this._buildHandler('onSelect');

  // Manual binding for public and internal methods.
  _this.focus = _this._focus.bind(_this);
  _this.blur = _this._blur.bind(_this);
  _this.setMode = _this._setMode.bind(_this);
  _this.exitCurrentMode = _this._exitCurrentMode.bind(_this);
  _this.restoreEditorDOM = _this._restoreEditorDOM.bind(_this);
  _this.setClipboard = _this._setClipboard.bind(_this);
  _this.getClipboard = _this._getClipboard.bind(_this);
  _this.getEditorKey = function () {
    return _this._editorKey;
  };
  _this.update = _this._update.bind(_this);
  _this.onDragEnter = _this._onDragEnter.bind(_this);
  _this.onDragLeave = _this._onDragLeave.bind(_this);

  // See '_restoreEditorDOM()'.
  _this.state = { containerKey: 0 };
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.Editor.defaultProps"></a>[module draft-js.Editor.defaultProps](#apidoc.module.draft-js.Editor.defaultProps)

#### <a name="apidoc.element.draft-js.Editor.defaultProps.blockRendererFn"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>blockRendererFn ()](#apidoc.element.draft-js.Editor.defaultProps.blockRendererFn)
- description and source-code
```javascript
blockRendererFn = function () {
  return arg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.defaultProps.blockStyleFn"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>blockStyleFn ()](#apidoc.element.draft-js.Editor.defaultProps.blockStyleFn)
- description and source-code
```javascript
blockStyleFn = function () {
  return arg;
}
```
- example usage
```shell
...

var configForType = blockRenderMap.get(blockType);
var wrapperTemplate = configForType.wrapper;

var _Element = configForType.element || blockRenderMap.get('unstyled').element;

var depth = _block.getDepth();
var className = this.props.blockStyleFn(_block);

// List items are special snowflakes, since we handle nesting and
// counters manually.
if (_Element === 'li') {
  var shouldResetCount = lastWrapperTemplate !== wrapperTemplate || currentDepth === null || depth > currentDepth;
  className = joinClasses(className, getListItemClasses(blockType, depth, shouldResetCount, direction));
}
...
```

#### <a name="apidoc.element.draft-js.Editor.defaultProps.keyBindingFn"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.defaultProps.</span>keyBindingFn (e)](#apidoc.element.draft-js.Editor.defaultProps.keyBindingFn)
- description and source-code
```javascript
function getDefaultKeyBinding(e) {
  switch (e.keyCode) {
    case 66:
      // B
      return hasCommandModifier(e) ? 'bold' : null;
    case 68:
      // D
      return isCtrlKeyCommand(e) ? 'delete' : null;
    case 72:
      // H
      return isCtrlKeyCommand(e) ? 'backspace' : null;
    case 73:
      // I
      return hasCommandModifier(e) ? 'italic' : null;
    case 74:
      // J
      return hasCommandModifier(e) ? 'code' : null;
    case 75:
      // K
      return !isWindows && isCtrlKeyCommand(e) ? 'secondary-cut' : null;
    case 77:
      // M
      return isCtrlKeyCommand(e) ? 'split-block' : null;
    case 79:
      // O
      return isCtrlKeyCommand(e) ? 'split-block' : null;
    case 84:
      // T
      return isOSX && isCtrlKeyCommand(e) ? 'transpose-characters' : null;
    case 85:
      // U
      return hasCommandModifier(e) ? 'underline' : null;
    case 87:
      // W
      return isOSX && isCtrlKeyCommand(e) ? 'backspace-word' : null;
    case 89:
      // Y
      if (isCtrlKeyCommand(e)) {
        return isWindows ? 'redo' : 'secondary-paste';
      }
      return null;
    case 90:
      // Z
      return getZCommand(e) || null;
    case Keys.RETURN:
      return 'split-block';
    case Keys.DELETE:
      return getDeleteCommand(e);
    case Keys.BACKSPACE:
      return getBackspaceCommand(e);
    // LEFT/RIGHT handlers serve as a workaround for a Firefox bug.
    case Keys.LEFT:
      return shouldFixFirefoxMovement && hasCommandModifier(e) ? 'move-selection-to-start-of-block' : null;
    case Keys.RIGHT:
      return shouldFixFirefoxMovement && hasCommandModifier(e) ? 'move-selection-to-end-of-block' : null;
    default:
      return null;
  }
}
```
- example usage
```shell
...
      // Insert a nbsp into the editor.
      var contentState = DraftModifier.replaceText(editorState.getCurrentContent(), editorState.getSelection(), '\xA0');
      editor.update(EditorState.push(editorState, contentState, 'insert-characters'));
      return;
    }
}

var command = editor.props.keyBindingFn(e);

// If no command is specified, allow keydown event to continue.
if (!command) {
  return;
}

if (command === 'undo') {
...
```



# <a name="apidoc.module.draft-js.Editor.prototype"></a>[module draft-js.Editor.prototype](#apidoc.module.draft-js.Editor.prototype)

#### <a name="apidoc.element.draft-js.Editor.prototype._blur"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_blur ()](#apidoc.element.draft-js.Editor.prototype._blur)
- description and source-code
```javascript
function _blur() {
  ReactDOM.findDOMNode(this.refs.editor).blur();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._buildHandler"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_buildHandler (eventName)](#apidoc.element.draft-js.Editor.prototype._buildHandler)
- description and source-code
```javascript
function _buildHandler(eventName) {
  var _this2 = this;

  return function (e) {
    if (!_this2.props.readOnly) {
      var method = _this2._handler && _this2._handler[eventName];
      method && method(_this2, e);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._exitCurrentMode"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_exitCurrentMode ()](#apidoc.element.draft-js.Editor.prototype._exitCurrentMode)
- description and source-code
```javascript
function _exitCurrentMode() {
  this.setMode('edit');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._focus"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_focus (scrollPosition)](#apidoc.element.draft-js.Editor.prototype._focus)
- description and source-code
```javascript
function _focus(scrollPosition) {
  var editorState = this.props.editorState;

  var alreadyHasFocus = editorState.getSelection().getHasFocus();
  var editorNode = ReactDOM.findDOMNode(this.refs.editor);

  var scrollParent = Style.getScrollParent(editorNode);

  var _ref = scrollPosition || getScrollPosition(scrollParent);

  var x = _ref.x;
  var y = _ref.y;


  editorNode.focus();
  if (scrollParent === window) {
    window.scrollTo(x, y);
  } else {
    Scroll.setTop(scrollParent, y);
  }

  // On Chrome and Safari, calling focus on contenteditable focuses the
  // cursor at the first character. This is something you don't expect when
  // you're clicking on an input element but not directly on a character.
  // Put the cursor back where it was before the blur.
  if (!alreadyHasFocus) {
    this.update(EditorState.forceSelection(editorState, editorState.getSelection()));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._getClipboard"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_getClipboard ()](#apidoc.element.draft-js.Editor.prototype._getClipboard)
- description and source-code
```javascript
function _getClipboard() {
  return this._clipboard;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._onDragEnter"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_onDragEnter ()](#apidoc.element.draft-js.Editor.prototype._onDragEnter)
- description and source-code
```javascript
function _onDragEnter() {
  this._dragCount++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._onDragLeave"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_onDragLeave ()](#apidoc.element.draft-js.Editor.prototype._onDragLeave)
- description and source-code
```javascript
function _onDragLeave() {
  this._dragCount--;
  if (this._dragCount === 0) {
    this.exitCurrentMode();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._renderPlaceholder"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_renderPlaceholder ()](#apidoc.element.draft-js.Editor.prototype._renderPlaceholder)
- description and source-code
```javascript
function _renderPlaceholder() {
  if (this._showPlaceholder()) {
    return React.createElement(DraftEditorPlaceholder, {
      text: nullthrows(this.props.placeholder),
      editorState: this.props.editorState,
      textAlignment: this.props.textAlignment,
      accessibilityID: this._placeholderAccessibilityID
    });
  }
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._restoreEditorDOM"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_restoreEditorDOM (scrollPosition)](#apidoc.element.draft-js.Editor.prototype._restoreEditorDOM)
- description and source-code
```javascript
function _restoreEditorDOM(scrollPosition) {
  var _this3 = this;

  this.setState({ containerKey: this.state.containerKey + 1 }, function () {
    _this3._focus(scrollPosition);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._setClipboard"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_setClipboard (clipboard)](#apidoc.element.draft-js.Editor.prototype._setClipboard)
- description and source-code
```javascript
function _setClipboard(clipboard) {
  this._clipboard = clipboard;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._setMode"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_setMode (mode)](#apidoc.element.draft-js.Editor.prototype._setMode)
- description and source-code
```javascript
function _setMode(mode) {
  this._handler = handlerMap[mode];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._showPlaceholder"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_showPlaceholder ()](#apidoc.element.draft-js.Editor.prototype._showPlaceholder)
- description and source-code
```javascript
function _showPlaceholder() {
  return !!this.props.placeholder && !this.props.editorState.isInCompositionMode() && !this.props.editorState.getCurrentContent().
hasText();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype._update"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>_update (editorState)](#apidoc.element.draft-js.Editor.prototype._update)
- description and source-code
```javascript
function _update(editorState) {
  this._latestEditorState = editorState;
  this.props.onChange(editorState);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>componentDidMount ()](#apidoc.element.draft-js.Editor.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  this.setMode('edit');

<span class="apidocCodeCommentSpan">  /**
   * IE has a hardcoded "feature" that attempts to convert link text into
   * anchors in contentEditable DOM. This breaks the editor's expectations of
   * the DOM, and control is lost. Disable it to make IE behave.
   * See: http://blogs.msdn.com/b/ieinternals/archive/2010/09/15/
   * ie9-beta-minor-change-list.aspx
   */
</span>  if (isIE) {
    document.execCommand('AutoUrlDetect', false, false);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>componentDidUpdate ()](#apidoc.element.draft-js.Editor.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
  this._blockSelectEvents = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype.componentWillUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>componentWillUpdate (nextProps)](#apidoc.element.draft-js.Editor.prototype.componentWillUpdate)
- description and source-code
```javascript
function componentWillUpdate(nextProps) {
  this._blockSelectEvents = true;
  this._latestEditorState = nextProps.editorState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Editor.prototype.render"></a>[function <span class="apidocSignatureSpan">draft-js.Editor.prototype.</span>render ()](#apidoc.element.draft-js.Editor.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props;
  var readOnly = _props.readOnly;
  var textAlignment = _props.textAlignment;

  var rootClass = cx({
    'DraftEditor/root': true,
    'DraftEditor/alignLeft': textAlignment === 'left',
    'DraftEditor/alignRight': textAlignment === 'right',
    'DraftEditor/alignCenter': textAlignment === 'center'
  });

  var contentStyle = {
    outline: 'none',
    whiteSpace: 'pre-wrap',
    wordWrap: 'break-word'
  };

  return React.createElement(
    'div',
    { className: rootClass },
    this._renderPlaceholder(),
    React.createElement(
      'div',
      {
        className: cx('DraftEditor/editorContainer'),
        key: 'editor' + this.state.containerKey,
        ref: 'editorContainer' },
      React.createElement(
        'div',
        {
          'aria-activedescendant': readOnly ? null : this.props.ariaActiveDescendantID,
          'aria-autocomplete': readOnly ? null : this.props.ariaAutoComplete,
          'aria-describedby': this._showPlaceholder() ? this._placeholderAccessibilityID : null,
          'aria-expanded': readOnly ? null : this.props.ariaExpanded,
          'aria-haspopup': readOnly ? null : this.props.ariaHasPopup,
          'aria-label': this.props.ariaLabel,
          'aria-owns': readOnly ? null : this.props.ariaOwneeID,
          className: cx('public/DraftEditor/content'),
          contentEditable: !readOnly,
          'data-testid': this.props.webDriverTestID,
          onBeforeInput: this._onBeforeInput,
          onBlur: this._onBlur,
          onCompositionEnd: this._onCompositionEnd,
          onCompositionStart: this._onCompositionStart,
          onCopy: this._onCopy,
          onCut: this._onCut,
          onDragEnd: this._onDragEnd,
          onDragEnter: this.onDragEnter,
          onDragLeave: this.onDragLeave,
          onDragOver: this._onDragOver,
          onDragStart: this._onDragStart,
          onDrop: this._onDrop,
          onFocus: this._onFocus,
          onInput: this._onInput,
          onKeyDown: this._onKeyDown,
          onKeyPress: this._onKeyPress,
          onKeyUp: this._onKeyUp,
          onMouseUp: this._onMouseUp,
          onPaste: this._onPaste,
          onSelect: this._onSelect,
          ref: 'editor',
          role: readOnly ? null : this.props.role || 'textbox',
          spellCheck: allowSpellCheck && this.props.spellCheck,
          style: contentStyle,
          suppressContentEditableWarning: true,
          tabIndex: this.props.tabIndex },
        React.createElement(DraftEditorContents, {
          blockRenderMap: this.props.blockRenderMap,
          blockRendererFn: this.props.blockRendererFn,
          blockStyleFn: this.props.blockStyleFn,
          customStyleMap: _extends({}, DefaultDraftInlineStyle, this.props.customStyleMap),
          customStyleFn: this.props.customStyleFn,
          editorKey: this._editorKey,
          editorState: this.props.editorState
        })
      )
    )
  );
}
```
- example usage
```shell
...
  render() {
    return (
        <Editor editorState={this.state.editorState} onChange={this.onChange} />
    );
  }
}

ReactDOM.render(
  <MyEditor />,
  document.getElementById('container')
);
'''

Because Draft.js supports unicode, you must have the following meta tag in the '<head>' '</head>' block of your HTML file:
...
```



# <a name="apidoc.module.draft-js.EditorBidiService"></a>[module draft-js.EditorBidiService](#apidoc.module.draft-js.EditorBidiService)

#### <a name="apidoc.element.draft-js.EditorBidiService.getDirectionMap"></a>[function <span class="apidocSignatureSpan">draft-js.EditorBidiService.</span>getDirectionMap (content, prevBidiMap)](#apidoc.element.draft-js.EditorBidiService.getDirectionMap)
- description and source-code
```javascript
function getDirectionMap(content, prevBidiMap) {
  if (!bidiService) {
    bidiService = new UnicodeBidiService();
  } else {
    bidiService.reset();
  }

  var blockMap = content.getBlockMap();
  var nextBidi = blockMap.valueSeq().map(function (block) {
    return nullthrows(bidiService).getDirection(block.getText());
  });
  var bidiMap = OrderedMap(blockMap.keySeq().zip(nextBidi));

  if (prevBidiMap != null && Immutable.is(prevBidiMap, bidiMap)) {
    return prevBidiMap;
  }

  return bidiMap;
}
```
- example usage
```shell
...
return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
  }

  DraftEditorContents.prototype.shouldComponentUpdate = function shouldComponentUpdate(nextProps) {
var prevEditorState = this.props.editorState;
var nextEditorState = nextProps.editorState;

var prevDirectionMap = prevEditorState.getDirectionMap();
var nextDirectionMap = nextEditorState.getDirectionMap();

// Text direction has changed for one or more blocks. We must re-render.
if (prevDirectionMap !== nextDirectionMap) {
  return true;
}
...
```



# <a name="apidoc.module.draft-js.EditorBlock"></a>[module draft-js.EditorBlock](#apidoc.module.draft-js.EditorBlock)

#### <a name="apidoc.element.draft-js.EditorBlock.EditorBlock"></a>[function <span class="apidocSignatureSpan">draft-js.</span>EditorBlock ()](#apidoc.element.draft-js.EditorBlock.EditorBlock)
- description and source-code
```javascript
function DraftEditorBlock() {
  _classCallCheck(this, DraftEditorBlock);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.EditorBlock.prototype"></a>[module draft-js.EditorBlock.prototype](#apidoc.module.draft-js.EditorBlock.prototype)

#### <a name="apidoc.element.draft-js.EditorBlock.prototype._renderChildren"></a>[function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>_renderChildren ()](#apidoc.element.draft-js.EditorBlock.prototype._renderChildren)
- description and source-code
```javascript
function _renderChildren() {
  var _this2 = this;

  var block = this.props.block;
  var blockKey = block.getKey();
  var text = block.getText();
  var lastLeafSet = this.props.tree.size - 1;
  var hasSelection = isBlockOnSelectionEdge(this.props.selection, blockKey);

  return this.props.tree.map(function (leafSet, ii) {
    var leavesForLeafSet = leafSet.get('leaves');
    var lastLeaf = leavesForLeafSet.size - 1;
    var leaves = leavesForLeafSet.map(function (leaf, jj) {
      var offsetKey = DraftOffsetKey.encode(blockKey, ii, jj);
      var start = leaf.get('start');
      var end = leaf.get('end');
      return React.createElement(DraftEditorLeaf, {
        key: offsetKey,
        offsetKey: offsetKey,
        blockKey: blockKey,
        start: start,
        selection: hasSelection ? _this2.props.selection : undefined,
        forceSelection: _this2.props.forceSelection,
        text: text.slice(start, end),
        styleSet: block.getInlineStyleAt(start),
        customStyleMap: _this2.props.customStyleMap,
        customStyleFn: _this2.props.customStyleFn,
        isLast: ii === lastLeafSet && jj === lastLeaf
      });
    }).toArray();

    var decoratorKey = leafSet.get('decoratorKey');
    if (decoratorKey == null) {
      return leaves;
    }

    if (!_this2.props.decorator) {
      return leaves;
    }

    var decorator = nullthrows(_this2.props.decorator);

    var DecoratorComponent = decorator.getComponentForKey(decoratorKey);
    if (!DecoratorComponent) {
      return leaves;
    }

    var decoratorProps = decorator.getPropsForKey(decoratorKey);
    var decoratorOffsetKey = DraftOffsetKey.encode(blockKey, ii, 0);
    var decoratedText = text.slice(leavesForLeafSet.first().get('start'), leavesForLeafSet.last().get('end'));

    // Resetting dir to the same value on a child node makes Chrome/Firefox
    // confused on cursor movement. See http://jsfiddle.net/d157kLck/3/
    var dir = UnicodeBidiDirection.getHTMLDirIfDifferent(UnicodeBidi.getDirection(decoratedText), _this2.props.direction);

    return React.createElement(
      DecoratorComponent,
      _extends({}, decoratorProps, {
        contentState: _this2.props.contentState,
        decoratedText: decoratedText,
        dir: dir,
        key: decoratorOffsetKey,
        entityKey: block.getEntityAt(leafSet.get('start')),
        offsetKey: decoratorOffsetKey }),
      leaves
    );
  }).toArray();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorBlock.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>componentDidMount ()](#apidoc.element.draft-js.EditorBlock.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  var selection = this.props.selection;
  var endKey = selection.getEndKey();
  if (!selection.getHasFocus() || endKey !== this.props.block.getKey()) {
    return;
  }

  var blockNode = ReactDOM.findDOMNode(this);
  var scrollParent = Style.getScrollParent(blockNode);
  var scrollPosition = getScrollPosition(scrollParent);
  var scrollDelta;

  if (scrollParent === window) {
    var nodePosition = getElementPosition(blockNode);
    var nodeBottom = nodePosition.y + nodePosition.height;
    var viewportHeight = getViewportDimensions().height;
    scrollDelta = nodeBottom - viewportHeight;
    if (scrollDelta > 0) {
      window.scrollTo(scrollPosition.x, scrollPosition.y + scrollDelta + SCROLL_BUFFER);
    }
  } else {
    var blockBottom = blockNode.offsetHeight + blockNode.offsetTop;
    var scrollBottom = scrollParent.offsetHeight + scrollPosition.y;
    scrollDelta = blockBottom - scrollBottom;
    if (scrollDelta > 0) {
      Scroll.setTop(scrollParent, Scroll.getTop(scrollParent) + scrollDelta + SCROLL_BUFFER);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorBlock.prototype.render"></a>[function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>render ()](#apidoc.element.draft-js.EditorBlock.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props;
  var direction = _props.direction;
  var offsetKey = _props.offsetKey;

  var className = cx({
    'public/DraftStyleDefault/block': true,
    'public/DraftStyleDefault/ltr': direction === 'LTR',
    'public/DraftStyleDefault/rtl': direction === 'RTL'
  });

  return React.createElement(
    'div',
    { 'data-offset-key': offsetKey, className: className },
    this._renderChildren()
  );
}
```
- example usage
```shell
...
  render() {
    return (
        <Editor editorState={this.state.editorState} onChange={this.onChange} />
    );
  }
}

ReactDOM.render(
  <MyEditor />,
  document.getElementById('container')
);
'''

Because Draft.js supports unicode, you must have the following meta tag in the '<head>' '</head>' block of your HTML file:
...
```

#### <a name="apidoc.element.draft-js.EditorBlock.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">draft-js.EditorBlock.prototype.</span>shouldComponentUpdate (nextProps)](#apidoc.element.draft-js.EditorBlock.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps) {
  return this.props.block !== nextProps.block || this.props.tree !== nextProps.tree || this.props.direction !== nextProps.direction
 || isBlockOnSelectionEdge(nextProps.selection, nextProps.block.getKey()) && nextProps.forceSelection;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.EditorState"></a>[module draft-js.EditorState](#apidoc.module.draft-js.EditorState)

#### <a name="apidoc.element.draft-js.EditorState.EditorState"></a>[function <span class="apidocSignatureSpan">draft-js.</span>EditorState (immutable)](#apidoc.element.draft-js.EditorState.EditorState)
- description and source-code
```javascript
function EditorState(immutable) {
  _classCallCheck(this, EditorState);

  this._immutable = immutable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.acceptSelection"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>acceptSelection (editorState, selection)](#apidoc.element.draft-js.EditorState.acceptSelection)
- description and source-code
```javascript
function acceptSelection(editorState, selection) {
  return updateSelection(editorState, selection, false);
}
```
- example usage
```shell
...
  var currentSelection = editorState.getSelection();
  if (!currentSelection.getHasFocus()) {
    return;
  }

  var selection = currentSelection.set('hasFocus', false);
  editor.props.onBlur && editor.props.onBlur(e);
  editor.update(EditorState.acceptSelection(editorState, selection));
}

module.exports = editOnBlur;
...
```

#### <a name="apidoc.element.draft-js.EditorState.create"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>create (config)](#apidoc.element.draft-js.EditorState.create)
- description and source-code
```javascript
function create(config) {
  var currentContent = config.currentContent;
  var decorator = config.decorator;

  var recordConfig = _extends({}, config, {
    treeMap: generateNewTreeMap(currentContent, decorator),
    directionMap: EditorBidiService.getDirectionMap(currentContent)
  });
  return new EditorState(new EditorStateRecord(recordConfig));
}
```
- example usage
```shell
...

var _extends = _assign || function (target) { for (var i = 1; i < arguments.length; i++) { var source = arguments[i]; for (var key
 in source) { if (Object.prototype.hasOwnProperty.call(source, key)) { target[key] = source[key]; } } } return target; };

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class
 as a function"); } }

function _possibleConstructorReturn(self, call) { if (!self) { throw new ReferenceError("this hasn't been initialised - super()
hasn't been called"); } return call && (typeof call === "object" || typeof call === "function") ? call : self; }

function _inherits(subClass, superClass) { if (typeof superClass !== "function" && superClass !== null) { throw new TypeError("Super
 expression must either be null or a function, not " + typeof superClass); } subClass.prototype = Object.create(superClass && superClass
.prototype, { constructor: { value: subClass, enumerable: false, writable: true, configurable: true } }); if (superClass) Object
.setPrototypeOf ? Object.setPrototypeOf(subClass, superClass) : subClass.__proto__ = superClass; }

var DraftEditorBlock = require('./DraftEditorBlock.react');
var DraftOffsetKey = require('./DraftOffsetKey');
var EditorState = require('./EditorState');
var React = require('react');

var cx = require('fbjs/lib/cx');
...
```

#### <a name="apidoc.element.draft-js.EditorState.createEmpty"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>createEmpty (decorator)](#apidoc.element.draft-js.EditorState.createEmpty)
- description and source-code
```javascript
function createEmpty(decorator) {
  return EditorState.createWithContent(ContentState.createFromText(''), decorator);
}
```
- example usage
```shell
...
import React from 'react';
import ReactDOM from 'react-dom';
import {Editor, EditorState} from 'draft-js';

class MyEditor extends React.Component {
constructor(props) {
  super(props);
  this.state = {editorState: EditorState.createEmpty()};
  this.onChange = (editorState) => this.setState({editorState});
}
render() {
  return (
      <Editor editorState={this.state.editorState} onChange={this.onChange} />
  );
}
...
```

#### <a name="apidoc.element.draft-js.EditorState.createWithContent"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>createWithContent (contentState, decorator)](#apidoc.element.draft-js.EditorState.createWithContent)
- description and source-code
```javascript
function createWithContent(contentState, decorator) {
  var firstKey = contentState.getBlockMap().first().getKey();
  return EditorState.create({
    currentContent: contentState,
    undoStack: Stack(),
    redoStack: Stack(),
    decorator: decorator || null,
    selection: SelectionState.createEmpty(firstKey)
  });
}
```
- example usage
```shell
...
var contentState = new ContentState({
  blockMap: blockMap,
  entityMap: Immutable.OrderedMap(),
  selectionBefore: selectionState,
  selectionAfter: selectionState
});

var editorState = EditorState.createWithContent(contentState);
editorState = EditorState.forceSelection(editorState, selectionState);

function getSampleStateForTesting() {
  return { editorState: editorState, contentState: contentState, selectionState: selectionState };
}

module.exports = getSampleStateForTesting;
...
```

#### <a name="apidoc.element.draft-js.EditorState.forceSelection"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>forceSelection (editorState, selection)](#apidoc.element.draft-js.EditorState.forceSelection)
- description and source-code
```javascript
function forceSelection(editorState, selection) {
  if (!selection.getHasFocus()) {
    selection = selection.set('hasFocus', true);
  }
  return updateSelection(editorState, selection, true);
}
```
- example usage
```shell
...

  // When the tab containing this text editor is hidden and the user does a
  // find-in-page in a _different_ tab, Chrome on Mac likes to forget what the
  // selection was right after sending this focus event and (if you let it)
  // moves the cursor back to the beginning of the editor, so we force the
  // selection here instead of simply accepting it in order to preserve the
  // old cursor position. See https://crbug.com/540004.
  editor.update(EditorState.forceSelection(editorState, selection));
}

module.exports = editOnFocus;
...
```

#### <a name="apidoc.element.draft-js.EditorState.moveFocusToEnd"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>moveFocusToEnd (editorState)](#apidoc.element.draft-js.EditorState.moveFocusToEnd)
- description and source-code
```javascript
function moveFocusToEnd(editorState) {
  var afterSelectionMove = EditorState.moveSelectionToEnd(editorState);
  return EditorState.forceSelection(afterSelectionMove, afterSelectionMove.getSelection());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.moveSelectionToEnd"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>moveSelectionToEnd (editorState)](#apidoc.element.draft-js.EditorState.moveSelectionToEnd)
- description and source-code
```javascript
function moveSelectionToEnd(editorState) {
  var content = editorState.getCurrentContent();
  var lastBlock = content.getLastBlock();
  var lastKey = lastBlock.getKey();
  var length = lastBlock.getLength();

  return EditorState.acceptSelection(editorState, new SelectionState({
    anchorKey: lastKey,
    anchorOffset: length,
    focusKey: lastKey,
    focusOffset: length,
    isBackward: false
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.push"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>push (editorState, contentState, changeType)](#apidoc.element.draft-js.EditorState.push)
- description and source-code
```javascript
function push(editorState, contentState, changeType) {
  if (editorState.getCurrentContent() === contentState) {
    return editorState;
  }

  var forceSelection = changeType !== 'insert-characters';
  var directionMap = EditorBidiService.getDirectionMap(contentState, editorState.getDirectionMap());

  if (!editorState.getAllowUndo()) {
    return EditorState.set(editorState, {
      currentContent: contentState,
      directionMap: directionMap,
      lastChangeType: changeType,
      selection: contentState.getSelectionAfter(),
      forceSelection: forceSelection,
      inlineStyleOverride: null
    });
  }

  var selection = editorState.getSelection();
  var currentContent = editorState.getCurrentContent();
  var undoStack = editorState.getUndoStack();
  var newContent = contentState;

  if (selection !== currentContent.getSelectionAfter() || mustBecomeBoundary(editorState, changeType)) {
    undoStack = undoStack.push(currentContent);
    newContent = newContent.set('selectionBefore', selection);
  } else if (changeType === 'insert-characters' || changeType === 'backspace-character' || changeType === 'delete-character') {
    // Preserve the previous selection.
    newContent = newContent.set('selectionBefore', currentContent.getSelectionBefore());
  }

  var inlineStyleOverride = editorState.getInlineStyleOverride();

  // Don't discard inline style overrides on block type or depth changes.
  if (changeType !== 'adjust-depth' && changeType !== 'change-block-type') {
    inlineStyleOverride = null;
  }

  var editorStateChanges = {
    currentContent: newContent,
    directionMap: directionMap,
    undoStack: undoStack,
    redoStack: Stack(),
    lastChangeType: changeType,
    selection: contentState.getSelectionAfter(),
    forceSelection: forceSelection,
    inlineStyleOverride: inlineStyleOverride
  };

  return EditorState.set(editorState, editorStateChanges);
}
```
- example usage
```shell
...

var leafSets = [];
var decorations = decorator ? decorator.getDecorations(block, contentState) : List(Repeat(null, textLength));

var chars = block.getCharacterList();

findRangesImmutable(decorations, areEqual, returnTrue, function (start, end) {
  leafSets.push(new DecoratorRange({
    start: start,
    end: end,
    decoratorKey: decorations.get(start),
    leaves: generateLeaves(chars.slice(start, end).toList(), start)
  }));
});
...
```

#### <a name="apidoc.element.draft-js.EditorState.redo"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>redo (editorState)](#apidoc.element.draft-js.EditorState.redo)
- description and source-code
```javascript
function redo(editorState) {
  if (!editorState.getAllowUndo()) {
    return editorState;
  }

  var redoStack = editorState.getRedoStack();
  var newCurrentContent = redoStack.peek();
  if (!newCurrentContent) {
    return editorState;
  }

  var currentContent = editorState.getCurrentContent();
  var directionMap = EditorBidiService.getDirectionMap(newCurrentContent, editorState.getDirectionMap());

  return EditorState.set(editorState, {
    currentContent: newCurrentContent,
    directionMap: directionMap,
    undoStack: editorState.getUndoStack().push(currentContent),
    redoStack: redoStack.shift(),
    forceSelection: true,
    inlineStyleOverride: null,
    lastChangeType: 'redo',
    nativelyRenderedContent: null,
    selection: newCurrentContent.getSelectionAfter()
  });
}
```
- example usage
```shell
...

/**
 * Map a 'DraftEditorCommand' command value to a corresponding function.
 */
function onKeyCommand(command, editorState) {
switch (command) {
  case 'redo':
    return EditorState.redo(editorState);
  case 'delete':
    return keyCommandPlainDelete(editorState);
  case 'delete-word':
    return keyCommandDeleteWord(editorState);
  case 'backspace':
    return keyCommandPlainBackspace(editorState);
  case 'backspace-word':
...
```

#### <a name="apidoc.element.draft-js.EditorState.set"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>set (editorState, put)](#apidoc.element.draft-js.EditorState.set)
- description and source-code
```javascript
function set(editorState, put) {
  var map = editorState.getImmutable().withMutations(function (state) {
    var existingDecorator = state.get('decorator');
    var decorator = existingDecorator;
    if (put.decorator === null) {
      decorator = null;
    } else if (put.decorator) {
      decorator = put.decorator;
    }

    var newContent = put.currentContent || editorState.getCurrentContent();

    if (decorator !== existingDecorator) {
      var treeMap = state.get('treeMap');
      var newTreeMap;
      if (decorator && existingDecorator) {
        newTreeMap = regenerateTreeForNewDecorator(newContent, newContent.getBlockMap(), treeMap, decorator, existingDecorator);
      } else {
        newTreeMap = generateNewTreeMap(newContent, decorator);
      }

      state.merge({
        decorator: decorator,
        treeMap: newTreeMap,
        nativelyRenderedContent: null
      });
      return;
    }

    var existingContent = editorState.getCurrentContent();
    if (newContent !== existingContent) {
      state.set('treeMap', regenerateTreeForNewBlocks(editorState, newContent.getBlockMap(), newContent.getEntityMap(), decorator
));
    }

    state.merge(put);
  });

  return new EditorState(map);
}
```
- example usage
```shell
...
    sliceEnd = blockKey === endKey ? endOffset : block.getLength();
  }

  var chars = block.getCharacterList();
  var current;
  while (sliceStart < sliceEnd) {
    current = chars.get(sliceStart);
    chars = chars.set(sliceStart, addOrRemove ? CharacterMetadata.applyStyle(current, inlineStyle) : CharacterMetadata.removeStyle
(current, inlineStyle));
    sliceStart++;
  }

  return block.set('characterList', chars);
});

return contentState.merge({
...
```

#### <a name="apidoc.element.draft-js.EditorState.setInlineStyleOverride"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>setInlineStyleOverride (editorState, inlineStyleOverride)](#apidoc.element.draft-js.EditorState.setInlineStyleOverride)
- description and source-code
```javascript
function setInlineStyleOverride(editorState, inlineStyleOverride) {
  return EditorState.set(editorState, { inlineStyleOverride: inlineStyleOverride });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.undo"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.</span>undo (editorState)](#apidoc.element.draft-js.EditorState.undo)
- description and source-code
```javascript
function undo(editorState) {
  if (!editorState.getAllowUndo()) {
    return editorState;
  }

  var undoStack = editorState.getUndoStack();
  var newCurrentContent = undoStack.peek();
  if (!newCurrentContent) {
    return editorState;
  }

  var currentContent = editorState.getCurrentContent();
  var directionMap = EditorBidiService.getDirectionMap(newCurrentContent, editorState.getDirectionMap());

  return EditorState.set(editorState, {
    currentContent: newCurrentContent,
    directionMap: directionMap,
    undoStack: undoStack.shift(),
    redoStack: editorState.getRedoStack().push(currentContent),
    forceSelection: true,
    inlineStyleOverride: null,
    lastChangeType: 'undo',
    nativelyRenderedContent: null,
    selection: currentContent.getSelectionBefore()
  });
}
```
- example usage
```shell
...
 */

'use strict';

var EditorState = require('./EditorState');

function keyCommandUndo(e, editorState, updateFn) {
var undoneState = EditorState.undo(editorState);

// If the last change to occur was a spellcheck change, allow the undo
// event to fall through to the browser. This allows the browser to record
// the unwanted change, which should soon lead it to learn not to suggest
// the correction again.
if (editorState.getLastChangeType() === 'spellcheck-change') {
  var nativelyRenderedContent = undoneState.getCurrentContent();
...
```



# <a name="apidoc.module.draft-js.EditorState.prototype"></a>[module draft-js.EditorState.prototype](#apidoc.module.draft-js.EditorState.prototype)

#### <a name="apidoc.element.draft-js.EditorState.prototype.getAllowUndo"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getAllowUndo ()](#apidoc.element.draft-js.EditorState.prototype.getAllowUndo)
- description and source-code
```javascript
function getAllowUndo() {
  return this.getImmutable().get('allowUndo');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getBlockTree"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getBlockTree (blockKey)](#apidoc.element.draft-js.EditorState.prototype.getBlockTree)
- description and source-code
```javascript
function getBlockTree(blockKey) {
  return this.getImmutable().getIn(['treeMap', blockKey]);
}
```
- example usage
```shell
...
  customStyleFn: customStyleFn,
  decorator: decorator,
  direction: direction,
  forceSelection: forceSelection,
  key: key,
  offsetKey: offsetKey,
  selection: selection,
  tree: editorState.getBlockTree(key)
};

var configForType = blockRenderMap.get(blockType);
var wrapperTemplate = configForType.wrapper;

var _Element = configForType.element || blockRenderMap.get('unstyled').element;
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getCurrentContent"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getCurrentContent ()](#apidoc.element.draft-js.EditorState.prototype.getCurrentContent)
- description and source-code
```javascript
function getCurrentContent() {
  return this.getImmutable().get('currentContent');
}
```
- example usage
```shell
...
textInputData = '';

var editorState = EditorState.set(editor._latestEditorState, {
  inCompositionMode: false
});

var currentStyle = editorState.getCurrentInlineStyle();
var entityKey = getEntityKeyForSelection(editorState.getCurrentContent(), editorState.getSelection());

var mustReset = !composedChars || isSelectionAtLeafStart(editorState) || currentStyle.size > 0 || entityKey !== null;

if (mustReset) {
  editor.restoreEditorDOM();
}
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getCurrentInlineStyle"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getCurrentInlineStyle ()](#apidoc.element.draft-js.EditorState.prototype.getCurrentInlineStyle)
- description and source-code
```javascript
function getCurrentInlineStyle() {
  var override = this.getInlineStyleOverride();
  if (override != null) {
    return override;
  }

  var content = this.getCurrentContent();
  var selection = this.getSelection();

  if (selection.isCollapsed()) {
    return getInlineStyleForCollapsedSelection(content, selection);
  }

  return getInlineStyleForNonCollapsedSelection(content, selection);
}
```
- example usage
```shell
...
var composedChars = textInputData;
textInputData = '';

var editorState = EditorState.set(editor._latestEditorState, {
  inCompositionMode: false
});

var currentStyle = editorState.getCurrentInlineStyle();
var entityKey = getEntityKeyForSelection(editorState.getCurrentContent(), editorState.getSelection());

var mustReset = !composedChars || isSelectionAtLeafStart(editorState) || currentStyle.size > 0 || entityKey !== null;

if (mustReset) {
  editor.restoreEditorDOM();
}
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getDecorator"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getDecorator ()](#apidoc.element.draft-js.EditorState.prototype.getDecorator)
- description and source-code
```javascript
function getDecorator() {
  return this.getImmutable().get('decorator');
}
```
- example usage
```shell
...
  // rendered state, there's nothing new to be done.
  if (prevEditorState === nextEditorState || nextNativeContent !== null && nextEditorState.getCurrentContent() === nextNativeContent
 || wasComposing && nowComposing) {
    return false;
  }

  var prevContent = prevEditorState.getCurrentContent();
  var nextContent = nextEditorState.getCurrentContent();
  var prevDecorator = prevEditorState.getDecorator();
  var nextDecorator = nextEditorState.getDecorator();
  return wasComposing !== nowComposing || prevContent !== nextContent || prevDecorator !== nextDecorator || nextEditorState.mustForceSelection
();
};

DraftEditorContents.prototype.render = function render() {
  var _props = this.props;
  var blockRenderMap = _props.blockRenderMap;
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getDirectionMap"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getDirectionMap ()](#apidoc.element.draft-js.EditorState.prototype.getDirectionMap)
- description and source-code
```javascript
function getDirectionMap() {
  return this.getImmutable().get('directionMap');
}
```
- example usage
```shell
...
return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
  }

  DraftEditorContents.prototype.shouldComponentUpdate = function shouldComponentUpdate(nextProps) {
var prevEditorState = this.props.editorState;
var nextEditorState = nextProps.editorState;

var prevDirectionMap = prevEditorState.getDirectionMap();
var nextDirectionMap = nextEditorState.getDirectionMap();

// Text direction has changed for one or more blocks. We must re-render.
if (prevDirectionMap !== nextDirectionMap) {
  return true;
}
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getImmutable"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getImmutable ()](#apidoc.element.draft-js.EditorState.prototype.getImmutable)
- description and source-code
```javascript
function getImmutable() {
  return this._immutable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getInlineStyleOverride"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getInlineStyleOverride ()](#apidoc.element.draft-js.EditorState.prototype.getInlineStyleOverride)
- description and source-code
```javascript
function getInlineStyleOverride() {
  return this.getImmutable().get('inlineStyleOverride');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getLastChangeType"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getLastChangeType ()](#apidoc.element.draft-js.EditorState.prototype.getLastChangeType)
- description and source-code
```javascript
function getLastChangeType() {
  return this.getImmutable().get('lastChangeType');
}
```
- example usage
```shell
...
function keyCommandUndo(e, editorState, updateFn) {
var undoneState = EditorState.undo(editorState);

// If the last change to occur was a spellcheck change, allow the undo
// event to fall through to the browser. This allows the browser to record
// the unwanted change, which should soon lead it to learn not to suggest
// the correction again.
if (editorState.getLastChangeType() === 'spellcheck-change') {
  var nativelyRenderedContent = undoneState.getCurrentContent();
  updateFn(EditorState.set(undoneState, { nativelyRenderedContent: nativelyRenderedContent }));
  return;
}

// Otheriwse, manage the undo behavior manually.
e.preventDefault();
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getNativelyRenderedContent"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getNativelyRenderedContent ()](#apidoc.element.draft-js.EditorState.prototype.getNativelyRenderedContent)
- description and source-code
```javascript
function getNativelyRenderedContent() {
  return this.getImmutable().get('nativelyRenderedContent');
}
```
- example usage
```shell
...
var didHaveFocus = prevEditorState.getSelection().getHasFocus();
var nowHasFocus = nextEditorState.getSelection().getHasFocus();

if (didHaveFocus !== nowHasFocus) {
  return true;
}

var nextNativeContent = nextEditorState.getNativelyRenderedContent();

var wasComposing = prevEditorState.isInCompositionMode();
var nowComposing = nextEditorState.isInCompositionMode();

// If the state is unchanged or we're currently rendering a natively
// rendered state, there's nothing new to be done.
if (prevEditorState === nextEditorState || nextNativeContent !== null && nextEditorState.getCurrentContent() === nextNativeContent
 || wasComposing && nowComposing) {
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getRedoStack"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getRedoStack ()](#apidoc.element.draft-js.EditorState.prototype.getRedoStack)
- description and source-code
```javascript
function getRedoStack() {
  return this.getImmutable().get('redoStack');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getSelection"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getSelection ()](#apidoc.element.draft-js.EditorState.prototype.getSelection)
- description and source-code
```javascript
function getSelection() {
  return this.getImmutable().get('selection');
}
```
- example usage
```shell
...
textInputData = '';

var editorState = EditorState.set(editor._latestEditorState, {
  inCompositionMode: false
});

var currentStyle = editorState.getCurrentInlineStyle();
var entityKey = getEntityKeyForSelection(editorState.getCurrentContent(), editorState.getSelection());

var mustReset = !composedChars || isSelectionAtLeafStart(editorState) || currentStyle.size > 0 || entityKey !== null;

if (mustReset) {
  editor.restoreEditorDOM();
}
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.getUndoStack"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>getUndoStack ()](#apidoc.element.draft-js.EditorState.prototype.getUndoStack)
- description and source-code
```javascript
function getUndoStack() {
  return this.getImmutable().get('undoStack');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.isInCompositionMode"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>isInCompositionMode ()](#apidoc.element.draft-js.EditorState.prototype.isInCompositionMode)
- description and source-code
```javascript
function isInCompositionMode() {
  return this.getImmutable().get('inCompositionMode');
}
```
- example usage
```shell
...

if (didHaveFocus !== nowHasFocus) {
  return true;
}

var nextNativeContent = nextEditorState.getNativelyRenderedContent();

var wasComposing = prevEditorState.isInCompositionMode();
var nowComposing = nextEditorState.isInCompositionMode();

// If the state is unchanged or we're currently rendering a natively
// rendered state, there's nothing new to be done.
if (prevEditorState === nextEditorState || nextNativeContent !== null && nextEditorState.getCurrentContent() === nextNativeContent
 || wasComposing && nowComposing) {
  return false;
}
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.isSelectionAtEndOfContent"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>isSelectionAtEndOfContent ()](#apidoc.element.draft-js.EditorState.prototype.isSelectionAtEndOfContent)
- description and source-code
```javascript
function isSelectionAtEndOfContent() {
  var content = this.getCurrentContent();
  var blockMap = content.getBlockMap();
  var last = blockMap.last();
  var end = last.getLength();
  return this.getSelection().hasEdgeWithin(last.getKey(), end, end);
}
```
- example usage
```shell
...
 */
function removeTextWithStrategy(editorState, strategy, direction) {
  var selection = editorState.getSelection();
  var content = editorState.getCurrentContent();
  var target = selection;
  if (selection.isCollapsed()) {
if (direction === 'forward') {
  if (editorState.isSelectionAtEndOfContent()) {
    return content;
  }
} else if (editorState.isSelectionAtStartOfContent()) {
  return content;
}

target = strategy(editorState);
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.isSelectionAtStartOfContent"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>isSelectionAtStartOfContent ()](#apidoc.element.draft-js.EditorState.prototype.isSelectionAtStartOfContent)
- description and source-code
```javascript
function isSelectionAtStartOfContent() {
  var firstKey = this.getCurrentContent().getBlockMap().first().getKey();
  return this.getSelection().hasEdgeWithin(firstKey, 0, 0);
}
```
- example usage
```shell
...
  var content = editorState.getCurrentContent();
  var target = selection;
  if (selection.isCollapsed()) {
if (direction === 'forward') {
  if (editorState.isSelectionAtEndOfContent()) {
    return content;
  }
} else if (editorState.isSelectionAtStartOfContent()) {
  return content;
}

target = strategy(editorState);
if (target === selection) {
  return content;
}
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.mustForceSelection"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>mustForceSelection ()](#apidoc.element.draft-js.EditorState.prototype.mustForceSelection)
- description and source-code
```javascript
function mustForceSelection() {
  return this.getImmutable().get('forceSelection');
}
```
- example usage
```shell
...
    return false;
  }

  var prevContent = prevEditorState.getCurrentContent();
  var nextContent = nextEditorState.getCurrentContent();
  var prevDecorator = prevEditorState.getDecorator();
  var nextDecorator = nextEditorState.getDecorator();
  return wasComposing !== nowComposing || prevContent !== nextContent || prevDecorator !== nextDecorator || nextEditorState.mustForceSelection
();
};

DraftEditorContents.prototype.render = function render() {
  var _props = this.props;
  var blockRenderMap = _props.blockRenderMap;
  var blockRendererFn = _props.blockRendererFn;
  var customStyleMap = _props.customStyleMap;
...
```

#### <a name="apidoc.element.draft-js.EditorState.prototype.toJS"></a>[function <span class="apidocSignatureSpan">draft-js.EditorState.prototype.</span>toJS ()](#apidoc.element.draft-js.EditorState.prototype.toJS)
- description and source-code
```javascript
function toJS() {
  return this.getImmutable().toJS();
}
```
- example usage
```shell
...
  var styleList = block.getCharacterList().map(function (c) {
    return c.getStyle();
  }).toList();
  var ranges = styleList.flatten().toSet().map(function (style) {
    return getEncodedInlinesForType(block, styleList, style);
  });

  return Array.prototype.concat.apply(EMPTY_ARRAY, ranges.toJS());
}

module.exports = encodeInlineStyleRanges;
...
```



# <a name="apidoc.module.draft-js.Entity"></a>[module draft-js.Entity](#apidoc.module.draft-js.Entity)

#### <a name="apidoc.element.draft-js.Entity.__add"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>__add (instance)](#apidoc.element.draft-js.Entity.__add)
- description and source-code
```javascript
function __add(instance) {
  var key = '' + ++instanceKey;
  instances = instances.set(key, instance);
  return key;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Entity.__create"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>__create (type, mutability, data)](#apidoc.element.draft-js.Entity.__create)
- description and source-code
```javascript
function __create(type, mutability, data) {
  return DraftEntity.__add(new DraftEntityInstance({ type: type, mutability: mutability, data: data || {} }));
}
```
- example usage
```shell
...
        entityConfig[attr] = imageAttribute;
      }
    });
    var imageURI = new URI(entityConfig.src).toString();
    node.textContent = imageURI; // Output src if no decorator

    // TODO: update this when we remove DraftEntity entirely
    inEntity = DraftEntity.__create('IMAGE', 'MUTABLE', entityConfig || {});
  })();
}

var chunk = getEmptyChunk();
var newChunk = null;

// Inline tags
...
```

#### <a name="apidoc.element.draft-js.Entity.__get"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>__get (key)](#apidoc.element.draft-js.Entity.__get)
- description and source-code
```javascript
function __get(key) {
  var instance = instances.get(key);
  !!!instance ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Unknown DraftEntity key.') : invariant(false) : void 0
;
  return instance;
}
```
- example usage
```shell
...
var start = selectionState.getStartOffset();
var end = selectionState.getEndOffset();
var entityKey = block.getEntityAt(start);
if (!entityKey) {
  return selectionState;
}

var entity = entityMap.__get(entityKey);
var mutability = entity.getMutability();

// 'MUTABLE' entities can just have the specified range of text removed
// directly. No adjustments are needed.
if (mutability === 'MUTABLE') {
  return selectionState;
}
...
```

#### <a name="apidoc.element.draft-js.Entity.__getLastCreatedEntityKey"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>__getLastCreatedEntityKey ()](#apidoc.element.draft-js.Entity.__getLastCreatedEntityKey)
- description and source-code
```javascript
function __getLastCreatedEntityKey() {
  return '' + instanceKey;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Entity.__mergeData"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>__mergeData (key, toMerge)](#apidoc.element.draft-js.Entity.__mergeData)
- description and source-code
```javascript
function __mergeData(key, toMerge) {
  var instance = DraftEntity.__get(key);
  var newData = _extends({}, instance.getData(), toMerge);
  var newInstance = instance.set('data', newData);
  instances = instances.set(key, newInstance);
  return newInstance;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Entity.__replaceData"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>__replaceData (key, newData)](#apidoc.element.draft-js.Entity.__replaceData)
- description and source-code
```javascript
function __replaceData(key, newData) {
  var instance = DraftEntity.__get(key);
  var newInstance = instance.set('data', newData);
  instances = instances.set(key, newInstance);
  return newInstance;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Entity.add"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>add (instance)](#apidoc.element.draft-js.Entity.add)
- description and source-code
```javascript
function add(instance) {
  logWarning('DraftEntity.add', 'contentState.addEntity');
  return DraftEntity.__add(instance);
}
```
- example usage
```shell
...
function getBlockMapSupportedTags(blockRenderMap) {
var unstyledElement = blockRenderMap.get('unstyled').element;
var tags = new Set([]);

blockRenderMap.forEach(function (draftBlock) {
  if (draftBlock.aliasedElements) {
    draftBlock.aliasedElements.forEach(function (tag) {
      tags = tags.add(tag);
    });
  }

  tags = tags.add(draftBlock.element);
});

return tags.filter(function (tag) {
...
```

#### <a name="apidoc.element.draft-js.Entity.create"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>create (type, mutability, data)](#apidoc.element.draft-js.Entity.create)
- description and source-code
```javascript
function create(type, mutability, data) {
  logWarning('DraftEntity.create', 'contentState.createEntity');
  return DraftEntity.__create(type, mutability, data);
}
```
- example usage
```shell
...

var _extends = _assign || function (target) { for (var i = 1; i < arguments.length; i++) { var source = arguments[i]; for (var key
 in source) { if (Object.prototype.hasOwnProperty.call(source, key)) { target[key] = source[key]; } } } return target; };

function _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError("Cannot call a class
 as a function"); } }

function _possibleConstructorReturn(self, call) { if (!self) { throw new ReferenceError("this hasn't been initialised - super()
hasn't been called"); } return call && (typeof call === "object" || typeof call === "function") ? call : self; }

function _inherits(subClass, superClass) { if (typeof superClass !== "function" && superClass !== null) { throw new TypeError("Super
 expression must either be null or a function, not " + typeof superClass); } subClass.prototype = Object.create(superClass && superClass
.prototype, { constructor: { value: subClass, enumerable: false, writable: true, configurable: true } }); if (superClass) Object
.setPrototypeOf ? Object.setPrototypeOf(subClass, superClass) : subClass.__proto__ = superClass; }

var DraftEditorBlock = require('./DraftEditorBlock.react');
var DraftOffsetKey = require('./DraftOffsetKey');
var EditorState = require('./EditorState');
var React = require('react');

var cx = require('fbjs/lib/cx');
...
```

#### <a name="apidoc.element.draft-js.Entity.get"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>get (key)](#apidoc.element.draft-js.Entity.get)
- description and source-code
```javascript
function get(key) {
  logWarning('DraftEntity.get', 'contentState.getEntity');
  return DraftEntity.__get(key);
}
```
- example usage
```shell
...

  var chars = block.getCharacterList();

  findRangesImmutable(decorations, areEqual, returnTrue, function (start, end) {
    leafSets.push(new DecoratorRange({
      start: start,
      end: end,
      decoratorKey: decorations.get(start),
      leaves: generateLeaves(chars.slice(start, end).toList(), start)
    }));
  });

  return List(leafSets);
},
...
```

#### <a name="apidoc.element.draft-js.Entity.getLastCreatedEntityKey"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>getLastCreatedEntityKey ()](#apidoc.element.draft-js.Entity.getLastCreatedEntityKey)
- description and source-code
```javascript
function getLastCreatedEntityKey() {
  logWarning('DraftEntity.getLastCreatedEntityKey', 'contentState.getLastCreatedEntityKey');
  return DraftEntity.__getLastCreatedEntityKey();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Entity.mergeData"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>mergeData (key, toMerge)](#apidoc.element.draft-js.Entity.mergeData)
- description and source-code
```javascript
function mergeData(key, toMerge) {
  logWarning('DraftEntity.mergeData', 'contentState.mergeEntityData');
  return DraftEntity.__mergeData(key, toMerge);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Entity.replaceData"></a>[function <span class="apidocSignatureSpan">draft-js.Entity.</span>replaceData (key, newData)](#apidoc.element.draft-js.Entity.replaceData)
- description and source-code
```javascript
function replaceData(key, newData) {
  logWarning('DraftEntity.replaceData', 'contentState.replaceEntityData');
  return DraftEntity.__replaceData(key, newData);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.EntityInstance"></a>[module draft-js.EntityInstance](#apidoc.module.draft-js.EntityInstance)

#### <a name="apidoc.element.draft-js.EntityInstance.EntityInstance"></a>[function <span class="apidocSignatureSpan">draft-js.</span>EntityInstance ()](#apidoc.element.draft-js.EntityInstance.EntityInstance)
- description and source-code
```javascript
function DraftEntityInstance() {
  _classCallCheck(this, DraftEntityInstance);

  return _possibleConstructorReturn(this, _DraftEntityInstanceR.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.EntityInstance.prototype"></a>[module draft-js.EntityInstance.prototype](#apidoc.module.draft-js.EntityInstance.prototype)

#### <a name="apidoc.element.draft-js.EntityInstance.prototype.getData"></a>[function <span class="apidocSignatureSpan">draft-js.EntityInstance.prototype.</span>getData ()](#apidoc.element.draft-js.EntityInstance.prototype.getData)
- description and source-code
```javascript
function getData() {
  return this.get('data');
}
```
- example usage
```shell
...
  rawBlocks.push({
    key: blockKey,
    text: block.getText(),
    type: block.getType(),
    depth: block.getDepth(),
    inlineStyleRanges: encodeInlineStyleRanges(block),
    entityRanges: encodeEntityRanges(block, entityStorageMap),
    data: block.getData().toObject()
  });
});

// Flip storage map so that our storage keys map to global
// DraftEntity keys.
var entityKeys = Object.keys(entityStorageMap);
var flippedStorageMap = {};
...
```

#### <a name="apidoc.element.draft-js.EntityInstance.prototype.getMutability"></a>[function <span class="apidocSignatureSpan">draft-js.EntityInstance.prototype.</span>getMutability ()](#apidoc.element.draft-js.EntityInstance.prototype.getMutability)
- description and source-code
```javascript
function getMutability() {
  return this.get('mutability');
}
```
- example usage
```shell
...
// DraftEntity keys.
var entityKeys = Object.keys(entityStorageMap);
var flippedStorageMap = {};
entityKeys.forEach(function (key, jj) {
  var entity = contentState.getEntity(DraftStringKey.unstringify(key));
  flippedStorageMap[jj] = {
    type: entity.getType(),
    mutability: entity.getMutability(),
    data: entity.getData()
  };
});

return {
  entityMap: flippedStorageMap,
  blocks: rawBlocks
...
```

#### <a name="apidoc.element.draft-js.EntityInstance.prototype.getType"></a>[function <span class="apidocSignatureSpan">draft-js.EntityInstance.prototype.</span>getType ()](#apidoc.element.draft-js.EntityInstance.prototype.getType)
- description and source-code
```javascript
function getType() {
  return this.get('type');
}
```
- example usage
```shell
...
    var processedBlocks = [];
    var currentDepth = null;
    var lastWrapperTemplate = null;

    for (var ii = 0; ii < blocksAsArray.length; ii++) {
var _block = blocksAsArray[ii];
var key = _block.getKey();
var blockType = _block.getType();

var customRenderer = blockRendererFn(_block);
var CustomComponent = void 0,
    customProps = void 0,
    customEditable = void 0;
if (customRenderer) {
  CustomComponent = customRenderer.component;
...
```



# <a name="apidoc.module.draft-js.KeyBindingUtil"></a>[module draft-js.KeyBindingUtil](#apidoc.module.draft-js.KeyBindingUtil)

#### <a name="apidoc.element.draft-js.KeyBindingUtil.hasCommandModifier"></a>[function <span class="apidocSignatureSpan">draft-js.KeyBindingUtil.</span>hasCommandModifier (e)](#apidoc.element.draft-js.KeyBindingUtil.hasCommandModifier)
- description and source-code
```javascript
function hasCommandModifier(e) {
  return isOSX ? !!e.metaKey && !e.altKey : KeyBindingUtil.isCtrlKeyCommand(e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.KeyBindingUtil.isCtrlKeyCommand"></a>[function <span class="apidocSignatureSpan">draft-js.KeyBindingUtil.</span>isCtrlKeyCommand (e)](#apidoc.element.draft-js.KeyBindingUtil.isCtrlKeyCommand)
- description and source-code
```javascript
function isCtrlKeyCommand(e) {
  return !!e.ctrlKey && !e.altKey;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.KeyBindingUtil.isOptionKeyCommand"></a>[function <span class="apidocSignatureSpan">draft-js.KeyBindingUtil.</span>isOptionKeyCommand (e)](#apidoc.element.draft-js.KeyBindingUtil.isOptionKeyCommand)
- description and source-code
```javascript
function isOptionKeyCommand(e) {
  return isOSX && e.altKey;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.Modifier"></a>[module draft-js.Modifier](#apidoc.module.draft-js.Modifier)

#### <a name="apidoc.element.draft-js.Modifier.applyEntity"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>applyEntity (contentState, selectionState, entityKey)](#apidoc.element.draft-js.Modifier.applyEntity)
- description and source-code
```javascript
function applyEntity(contentState, selectionState, entityKey) {
  var withoutEntities = removeEntitiesAtEdges(contentState, selectionState);
  return applyEntityToContentState(withoutEntities, selectionState, entityKey);
}
```
- example usage
```shell
...
'use strict';

var CharacterMetadata = require('./CharacterMetadata');

function applyEntityToContentBlock(contentBlock, start, end, entityKey) {
  var characterList = contentBlock.getCharacterList();
  while (start < end) {
    characterList = characterList.set(start, CharacterMetadata.applyEntity(characterList.get(start), entityKey));
    start++;
  }
  return contentBlock.set('characterList', characterList);
}

module.exports = applyEntityToContentBlock;
...
```

#### <a name="apidoc.element.draft-js.Modifier.applyInlineStyle"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>applyInlineStyle (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.Modifier.applyInlineStyle)
- description and source-code
```javascript
function applyInlineStyle(contentState, selectionState, inlineStyle) {
  return ContentStateInlineStyle.add(contentState, selectionState, inlineStyle);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Modifier.insertText"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>insertText (contentState, targetRange, text, inlineStyle, entityKey)](#apidoc.element.draft-js.Modifier.insertText)
- description and source-code
```javascript
function insertText(contentState, targetRange, text, inlineStyle, entityKey) {
  !targetRange.isCollapsed() ? process.env.NODE_ENV !== 'production' ? invariant(false, 'Target range must be collapsed for 'insertText
'.') : invariant(false) : void 0;
  return DraftModifier.replaceText(contentState, targetRange, text, inlineStyle, entityKey);
}
```
- example usage
```shell
...
  return EditorState.push(editorState, newContentState, 'insert-fragment');
}

/**
 * Insert text at a specified selection.
 */
function insertTextAtSelection(editorState, selection, text) {
  var newContentState = DraftModifier.insertText(editorState.getCurrentContent(), selection, text, editorState.getCurrentInlineStyle
());
  return EditorState.push(editorState, newContentState, 'insert-fragment');
}

module.exports = DraftEditorDragHandler;
...
```

#### <a name="apidoc.element.draft-js.Modifier.mergeBlockData"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>mergeBlockData (contentState, selectionState, blockData)](#apidoc.element.draft-js.Modifier.mergeBlockData)
- description and source-code
```javascript
function mergeBlockData(contentState, selectionState, blockData) {
  return modifyBlockForContentState(contentState, selectionState, function (block) {
    return block.merge({ data: block.getData().merge(blockData) });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Modifier.moveText"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>moveText (contentState, removalRange, targetRange)](#apidoc.element.draft-js.Modifier.moveText)
- description and source-code
```javascript
function moveText(contentState, removalRange, targetRange) {
  var movedFragment = getContentStateFragment(contentState, removalRange);

  var afterRemoval = DraftModifier.removeRange(contentState, removalRange, 'backward');

  return DraftModifier.replaceWithFragment(afterRemoval, targetRange, movedFragment);
}
```
- example usage
```shell
...

    editor.update(insertTextAtSelection(editorState, dropSelection, data.getText()));
  }

};

function moveText(editorState, targetSelection) {
  var newContentState = DraftModifier.moveText(editorState.getCurrentContent(), editorState.getSelection(), targetSelection);
  return EditorState.push(editorState, newContentState, 'insert-fragment');
}

/**
 * Insert text at a specified selection.
 */
function insertTextAtSelection(editorState, selection, text) {
...
```

#### <a name="apidoc.element.draft-js.Modifier.removeInlineStyle"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>removeInlineStyle (contentState, selectionState, inlineStyle)](#apidoc.element.draft-js.Modifier.removeInlineStyle)
- description and source-code
```javascript
function removeInlineStyle(contentState, selectionState, inlineStyle) {
  return ContentStateInlineStyle.remove(contentState, selectionState, inlineStyle);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Modifier.removeRange"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>removeRange (contentState, rangeToRemove, removalDirection)](#apidoc.element.draft-js.Modifier.removeRange)
- description and source-code
```javascript
function removeRange(contentState, rangeToRemove, removalDirection) {
  // Check whether the selection state overlaps with a single entity.
  // If so, try to remove the appropriate substring of the entity text.
  if (rangeToRemove.getAnchorKey() === rangeToRemove.getFocusKey()) {
    var key = rangeToRemove.getAnchorKey();
    var startOffset = rangeToRemove.getStartOffset();
    var endOffset = rangeToRemove.getEndOffset();
    var block = contentState.getBlockForKey(key);

    var startEntity = block.getEntityAt(startOffset);
    var endEntity = block.getEntityAt(endOffset - 1);
    if (startEntity && startEntity === endEntity) {
      var adjustedRemovalRange = getCharacterRemovalRange(contentState.getEntityMap(), block, rangeToRemove, removalDirection);
      return removeRangeFromContentState(contentState, adjustedRemovalRange);
    }
  }

  var withoutEntities = removeEntitiesAtEdges(contentState, rangeToRemove);
  return removeRangeFromContentState(withoutEntities, rangeToRemove);
}
```
- example usage
```shell
...
  } else {
    targetRange = selection;
  }

  targetRange = nullthrows(targetRange);
  clipboard = getContentStateFragment(content, targetRange);

  var afterRemoval = DraftModifier.removeRange(content, targetRange, 'forward');

  if (afterRemoval === content) {
    return editorState;
  }

  return EditorState.push(editorState, afterRemoval, 'remove-range');
},
...
```

#### <a name="apidoc.element.draft-js.Modifier.replaceText"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>replaceText (contentState, rangeToReplace, text, inlineStyle, entityKey)](#apidoc.element.draft-js.Modifier.replaceText)
- description and source-code
```javascript
function replaceText(contentState, rangeToReplace, text, inlineStyle, entityKey) {
  var withoutEntities = removeEntitiesAtEdges(contentState, rangeToReplace);
  var withoutText = removeRangeFromContentState(withoutEntities, rangeToReplace);

  var character = CharacterMetadata.create({
    style: inlineStyle || OrderedSet(),
    entity: entityKey || null
  });

  return insertTextIntoContentState(withoutText, withoutText.getSelectionAfter(), text, character);
}
```
- example usage
```shell
...
}

editor.exitCurrentMode();

if (composedChars) {
  // If characters have been composed, re-rendering with the update
  // is sufficient to reset the editor.
  var contentState = DraftModifier.replaceText(editorState.getCurrentContent(), editorState.getSelection(), composedChars, currentStyle
, entityKey);
  editor.update(EditorState.push(editorState, contentState, 'insert-characters'));
  return;
}

if (mustReset) {
  editor.update(EditorState.set(editorState, {
    nativelyRenderedContent: null,
...
```

#### <a name="apidoc.element.draft-js.Modifier.replaceWithFragment"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>replaceWithFragment (contentState, targetRange, fragment)](#apidoc.element.draft-js.Modifier.replaceWithFragment)
- description and source-code
```javascript
function replaceWithFragment(contentState, targetRange, fragment) {
  var withoutEntities = removeEntitiesAtEdges(contentState, targetRange);
  var withoutText = removeRangeFromContentState(withoutEntities, targetRange);

  return insertFragmentIntoContentState(withoutText, withoutText.getSelectionAfter(), fragment);
}
```
- example usage
```shell
...
  },

  paste: function paste(editorState) {
    if (!clipboard) {
      return editorState;
    }

    var newContent = DraftModifier.replaceWithFragment(editorState.getCurrentContent(), editorState.getSelection(), clipboard);

    return EditorState.push(editorState, newContent, 'insert-fragment');
  }
};

module.exports = SecondaryClipboard;
...
```

#### <a name="apidoc.element.draft-js.Modifier.setBlockData"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>setBlockData (contentState, selectionState, blockData)](#apidoc.element.draft-js.Modifier.setBlockData)
- description and source-code
```javascript
function setBlockData(contentState, selectionState, blockData) {
  return modifyBlockForContentState(contentState, selectionState, function (block) {
    return block.merge({ data: blockData });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Modifier.setBlockType"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>setBlockType (contentState, selectionState, blockType)](#apidoc.element.draft-js.Modifier.setBlockType)
- description and source-code
```javascript
function setBlockType(contentState, selectionState, blockType) {
  return modifyBlockForContentState(contentState, selectionState, function (block) {
    return block.merge({ type: blockType, depth: 0 });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.Modifier.splitBlock"></a>[function <span class="apidocSignatureSpan">draft-js.Modifier.</span>splitBlock (contentState, selectionState)](#apidoc.element.draft-js.Modifier.splitBlock)
- description and source-code
```javascript
function splitBlock(contentState, selectionState) {
  var withoutEntities = removeEntitiesAtEdges(contentState, selectionState);
  var withoutText = removeRangeFromContentState(withoutEntities, selectionState);

  return splitBlockInContentState(withoutText, withoutText.getSelectionAfter());
}
```
- example usage
```shell
...

'use strict';

var DraftModifier = require('./DraftModifier');
var EditorState = require('./EditorState');

function keyCommandInsertNewline(editorState) {
  var contentState = DraftModifier.splitBlock(editorState.getCurrentContent(), editorState.getSelection());
  return EditorState.push(editorState, contentState, 'split-block');
}

module.exports = keyCommandInsertNewline;
...
```



# <a name="apidoc.module.draft-js.RichUtils"></a>[module draft-js.RichUtils](#apidoc.module.draft-js.RichUtils)

#### <a name="apidoc.element.draft-js.RichUtils.currentBlockContainsLink"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>currentBlockContainsLink (editorState)](#apidoc.element.draft-js.RichUtils.currentBlockContainsLink)
- description and source-code
```javascript
function currentBlockContainsLink(editorState) {
  var selection = editorState.getSelection();
  var contentState = editorState.getCurrentContent();
  var entityMap = contentState.getEntityMap();
  return contentState.getBlockForKey(selection.getAnchorKey()).getCharacterList().slice(selection.getStartOffset(), selection.getEndOffset
()).some(function (v) {
    var entity = v.getEntity();
    return !!entity && entityMap.__get(entity).getType() === 'LINK';
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.getCurrentBlockType"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>getCurrentBlockType (editorState)](#apidoc.element.draft-js.RichUtils.getCurrentBlockType)
- description and source-code
```javascript
function getCurrentBlockType(editorState) {
  var selection = editorState.getSelection();
  return editorState.getCurrentContent().getBlockForKey(selection.getStartKey()).getType();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.getDataObjectForLinkURL"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>getDataObjectForLinkURL (uri)](#apidoc.element.draft-js.RichUtils.getDataObjectForLinkURL)
- description and source-code
```javascript
function getDataObjectForLinkURL(uri) {
  return { url: uri.toString() };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.handleKeyCommand"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>handleKeyCommand (editorState, command)](#apidoc.element.draft-js.RichUtils.handleKeyCommand)
- description and source-code
```javascript
function handleKeyCommand(editorState, command) {
  switch (command) {
    case 'bold':
      return RichTextEditorUtil.toggleInlineStyle(editorState, 'BOLD');
    case 'italic':
      return RichTextEditorUtil.toggleInlineStyle(editorState, 'ITALIC');
    case 'underline':
      return RichTextEditorUtil.toggleInlineStyle(editorState, 'UNDERLINE');
    case 'code':
      return RichTextEditorUtil.toggleCode(editorState);
    case 'backspace':
    case 'backspace-word':
    case 'backspace-to-start-of-line':
      return RichTextEditorUtil.onBackspace(editorState);
    case 'delete':
    case 'delete-word':
    case 'delete-to-end-of-block':
      return RichTextEditorUtil.onDelete(editorState);
    default:
      // they may have custom editor commands; ignore those
      return null;
  }
}
```
- example usage
```shell
...
}

// At this point, we know that we're handling a command of some kind, so
// we don't want to insert a character following the keydown.
e.preventDefault();

// Allow components higher up the tree to handle the command first.
if (editor.props.handleKeyCommand && isEventHandled(editor.props.handleKeyCommand(command))) {
  return;
}

var newState = onKeyCommand(command, editorState);
if (newState !== editorState) {
  editor.update(newState);
}
...
```

#### <a name="apidoc.element.draft-js.RichUtils.insertSoftNewline"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>insertSoftNewline (editorState)](#apidoc.element.draft-js.RichUtils.insertSoftNewline)
- description and source-code
```javascript
function insertSoftNewline(editorState) {
  var contentState = DraftModifier.insertText(editorState.getCurrentContent(), editorState.getSelection(), '\n', editorState.getCurrentInlineStyle
(), null);

  var newEditorState = EditorState.push(editorState, contentState, 'insert-characters');

  return EditorState.forceSelection(newEditorState, contentState.getSelectionAfter());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.onBackspace"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>onBackspace (editorState)](#apidoc.element.draft-js.RichUtils.onBackspace)
- description and source-code
```javascript
function onBackspace(editorState) {
  var selection = editorState.getSelection();
  if (!selection.isCollapsed() || selection.getAnchorOffset() || selection.getFocusOffset()) {
    return null;
  }

  // First, try to remove a preceding atomic block.
  var content = editorState.getCurrentContent();
  var startKey = selection.getStartKey();
  var blockBefore = content.getBlockBefore(startKey);

  if (blockBefore && blockBefore.getType() === 'atomic') {
    var blockMap = content.getBlockMap()['delete'](blockBefore.getKey());
    var withoutAtomicBlock = content.merge({ blockMap: blockMap, selectionAfter: selection });
    if (withoutAtomicBlock !== content) {
      return EditorState.push(editorState, withoutAtomicBlock, 'remove-range');
    }
  }

  // If that doesn't succeed, try to remove the current block style.
  var withoutBlockStyle = RichTextEditorUtil.tryToRemoveBlockStyle(editorState);

  if (withoutBlockStyle) {
    return EditorState.push(editorState, withoutBlockStyle, 'change-block-type');
  }

  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.onDelete"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>onDelete (editorState)](#apidoc.element.draft-js.RichUtils.onDelete)
- description and source-code
```javascript
function onDelete(editorState) {
  var selection = editorState.getSelection();
  if (!selection.isCollapsed()) {
    return null;
  }

  var content = editorState.getCurrentContent();
  var startKey = selection.getStartKey();
  var block = content.getBlockForKey(startKey);
  var length = block.getLength();

  // The cursor is somewhere within the text. Behave normally.
  if (selection.getStartOffset() < length) {
    return null;
  }

  var blockAfter = content.getBlockAfter(startKey);

  if (!blockAfter || blockAfter.getType() !== 'atomic') {
    return null;
  }

  var atomicBlockTarget = selection.merge({
    focusKey: blockAfter.getKey(),
    focusOffset: blockAfter.getLength()
  });

  var withoutAtomicBlock = DraftModifier.removeRange(content, atomicBlockTarget, 'forward');

  if (withoutAtomicBlock !== content) {
    return EditorState.push(editorState, withoutAtomicBlock, 'remove-range');
  }

  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.onTab"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>onTab (event, editorState, maxDepth)](#apidoc.element.draft-js.RichUtils.onTab)
- description and source-code
```javascript
function onTab(event, editorState, maxDepth) {
  var selection = editorState.getSelection();
  var key = selection.getAnchorKey();
  if (key !== selection.getFocusKey()) {
    return editorState;
  }

  var content = editorState.getCurrentContent();
  var block = content.getBlockForKey(key);
  var type = block.getType();
  if (type !== 'unordered-list-item' && type !== 'ordered-list-item') {
    return editorState;
  }

  event.preventDefault();

  // Only allow indenting one level beyond the block above, and only if
  // the block above is a list item as well.
  var blockAbove = content.getBlockBefore(key);
  if (!blockAbove) {
    return editorState;
  }

  var typeAbove = blockAbove.getType();
  if (typeAbove !== 'unordered-list-item' && typeAbove !== 'ordered-list-item') {
    return editorState;
  }

  var depth = block.getDepth();
  if (!event.shiftKey && depth === maxDepth) {
    return editorState;
  }

  maxDepth = Math.min(blockAbove.getDepth() + 1, maxDepth);

  var withAdjustment = adjustBlockDepthForContentState(content, selection, event.shiftKey ? -1 : 1, maxDepth);

  return EditorState.push(editorState, withAdjustment, 'adjust-depth');
}
```
- example usage
```shell
...
  }
  break;
case Keys.ESC:
  e.preventDefault();
  editor.props.onEscape && editor.props.onEscape(e);
  return;
case Keys.TAB:
  editor.props.onTab && editor.props.onTab(e);
  return;
case Keys.UP:
  editor.props.onUpArrow && editor.props.onUpArrow(e);
  return;
case Keys.DOWN:
  editor.props.onDownArrow && editor.props.onDownArrow(e);
  return;
...
```

#### <a name="apidoc.element.draft-js.RichUtils.toggleBlockType"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleBlockType (editorState, blockType)](#apidoc.element.draft-js.RichUtils.toggleBlockType)
- description and source-code
```javascript
function toggleBlockType(editorState, blockType) {
  var selection = editorState.getSelection();
  var startKey = selection.getStartKey();
  var endKey = selection.getEndKey();
  var content = editorState.getCurrentContent();
  var target = selection;

  // Triple-click can lead to a selection that includes offset 0 of the
  // following block. The 'SelectionState' for this case is accurate, but
  // we should avoid toggling block type for the trailing block because it
  // is a confusing interaction.
  if (startKey !== endKey && selection.getEndOffset() === 0) {
    var blockBefore = nullthrows(content.getBlockBefore(endKey));
    endKey = blockBefore.getKey();
    target = target.merge({
      anchorKey: startKey,
      anchorOffset: selection.getStartOffset(),
      focusKey: endKey,
      focusOffset: blockBefore.getLength(),
      isBackward: false
    });
  }

  var hasAtomicBlock = content.getBlockMap().skipWhile(function (_, k) {
    return k !== startKey;
  }).reverse().skipWhile(function (_, k) {
    return k !== endKey;
  }).some(function (v) {
    return v.getType() === 'atomic';
  });

  if (hasAtomicBlock) {
    return editorState;
  }

  var typeToSet = content.getBlockForKey(startKey).getType() === blockType ? 'unstyled' : blockType;

  return EditorState.push(editorState, DraftModifier.setBlockType(content, target, typeToSet), 'change-block-type');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.toggleCode"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleCode (editorState)](#apidoc.element.draft-js.RichUtils.toggleCode)
- description and source-code
```javascript
function toggleCode(editorState) {
  var selection = editorState.getSelection();
  var anchorKey = selection.getAnchorKey();
  var focusKey = selection.getFocusKey();

  if (selection.isCollapsed() || anchorKey !== focusKey) {
    return RichTextEditorUtil.toggleBlockType(editorState, 'code-block');
  }

  return RichTextEditorUtil.toggleInlineStyle(editorState, 'CODE');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.toggleInlineStyle"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleInlineStyle (editorState, inlineStyle)](#apidoc.element.draft-js.RichUtils.toggleInlineStyle)
- description and source-code
```javascript
function toggleInlineStyle(editorState, inlineStyle) {
  var selection = editorState.getSelection();
  var currentStyle = editorState.getCurrentInlineStyle();

  // If the selection is collapsed, toggle the specified style on or off and
  // set the result as the new inline style override. This will then be
  // used as the inline style for the next character to be inserted.
  if (selection.isCollapsed()) {
    return EditorState.setInlineStyleOverride(editorState, currentStyle.has(inlineStyle) ? currentStyle.remove(inlineStyle) : currentStyle
.add(inlineStyle));
  }

  // If characters are selected, immediately apply or remove the
  // inline style on the document state itself.
  var content = editorState.getCurrentContent();
  var newContent;

  // If the style is already present for the selection range, remove it.
  // Otherwise, apply it.
  if (currentStyle.has(inlineStyle)) {
    newContent = DraftModifier.removeInlineStyle(content, selection, inlineStyle);
  } else {
    newContent = DraftModifier.applyInlineStyle(content, selection, inlineStyle);
  }

  return EditorState.push(editorState, newContent, 'change-inline-style');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.toggleLink"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>toggleLink (editorState, targetSelection, entityKey)](#apidoc.element.draft-js.RichUtils.toggleLink)
- description and source-code
```javascript
function toggleLink(editorState, targetSelection, entityKey) {
  var withoutLink = DraftModifier.applyEntity(editorState.getCurrentContent(), targetSelection, entityKey);

  return EditorState.push(editorState, withoutLink, 'apply-entity');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.RichUtils.tryToRemoveBlockStyle"></a>[function <span class="apidocSignatureSpan">draft-js.RichUtils.</span>tryToRemoveBlockStyle (editorState)](#apidoc.element.draft-js.RichUtils.tryToRemoveBlockStyle)
- description and source-code
```javascript
function tryToRemoveBlockStyle(editorState) {
  var selection = editorState.getSelection();
  var offset = selection.getAnchorOffset();
  if (selection.isCollapsed() && offset === 0) {
    var key = selection.getAnchorKey();
    var content = editorState.getCurrentContent();
    var block = content.getBlockForKey(key);
    if (block.getLength() > 0) {
      return null;
    }

    var type = block.getType();
    var blockBefore = content.getBlockBefore(key);
    if (type === 'code-block' && blockBefore && blockBefore.getType() === 'code-block') {
      return null;
    }

    if (type !== 'unstyled') {
      return DraftModifier.setBlockType(content, selection, 'unstyled');
    }
  }
  return null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.draft-js.SecondaryClipboard"></a>[module draft-js.SecondaryClipboard](#apidoc.module.draft-js.SecondaryClipboard)

#### <a name="apidoc.element.draft-js.SecondaryClipboard.cut"></a>[function <span class="apidocSignatureSpan">draft-js.SecondaryClipboard.</span>cut (editorState)](#apidoc.element.draft-js.SecondaryClipboard.cut)
- description and source-code
```javascript
function cut(editorState) {
  var content = editorState.getCurrentContent();
  var selection = editorState.getSelection();
  var targetRange = null;

  if (selection.isCollapsed()) {
    var anchorKey = selection.getAnchorKey();
    var blockEnd = content.getBlockForKey(anchorKey).getLength();

    if (blockEnd === selection.getAnchorOffset()) {
      return editorState;
    }

    targetRange = selection.set('focusOffset', blockEnd);
  } else {
    targetRange = selection;
  }

  targetRange = nullthrows(targetRange);
  clipboard = getContentStateFragment(content, targetRange);

  var afterRemoval = DraftModifier.removeRange(content, targetRange, 'forward');

  if (afterRemoval === content) {
    return editorState;
  }

  return EditorState.push(editorState, afterRemoval, 'remove-range');
}
```
- example usage
```shell
...
    case 'transpose-characters':
      return keyCommandTransposeCharacters(editorState);
    case 'move-selection-to-start-of-block':
      return keyCommandMoveSelectionToStartOfBlock(editorState);
    case 'move-selection-to-end-of-block':
      return keyCommandMoveSelectionToEndOfBlock(editorState);
    case 'secondary-cut':
      return SecondaryClipboard.cut(editorState);
    case 'secondary-paste':
      return SecondaryClipboard.paste(editorState);
    default:
      return editorState;
  }
}
...
```

#### <a name="apidoc.element.draft-js.SecondaryClipboard.paste"></a>[function <span class="apidocSignatureSpan">draft-js.SecondaryClipboard.</span>paste (editorState)](#apidoc.element.draft-js.SecondaryClipboard.paste)
- description and source-code
```javascript
function paste(editorState) {
  if (!clipboard) {
    return editorState;
  }

  var newContent = DraftModifier.replaceWithFragment(editorState.getCurrentContent(), editorState.getSelection(), clipboard);

  return EditorState.push(editorState, newContent, 'insert-fragment');
}
```
- example usage
```shell
...
   case 'move-selection-to-start-of-block':
     return keyCommandMoveSelectionToStartOfBlock(editorState);
   case 'move-selection-to-end-of-block':
     return keyCommandMoveSelectionToEndOfBlock(editorState);
   case 'secondary-cut':
     return SecondaryClipboard.cut(editorState);
   case 'secondary-paste':
     return SecondaryClipboard.paste(editorState);
   default:
     return editorState;
 }
}

/**
* Intercept keydown behavior to handle keys and commands manually, if desired.
...
```



# <a name="apidoc.module.draft-js.SelectionState"></a>[module draft-js.SelectionState](#apidoc.module.draft-js.SelectionState)

#### <a name="apidoc.element.draft-js.SelectionState.SelectionState"></a>[function <span class="apidocSignatureSpan">draft-js.</span>SelectionState ()](#apidoc.element.draft-js.SelectionState.SelectionState)
- description and source-code
```javascript
function SelectionState() {
  _classCallCheck(this, SelectionState);

  return _possibleConstructorReturn(this, _SelectionStateRecord.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.draft-js.SelectionState.createEmpty"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.</span>createEmpty (key)](#apidoc.element.draft-js.SelectionState.createEmpty)
- description and source-code
```javascript
function createEmpty(key) {
  return new SelectionState({
    anchorKey: key,
    anchorOffset: 0,
    focusKey: key,
    focusOffset: 0,
    isBackward: false,
    hasFocus: false
  });
}
```
- example usage
```shell
...
import React from 'react';
import ReactDOM from 'react-dom';
import {Editor, EditorState} from 'draft-js';

class MyEditor extends React.Component {
constructor(props) {
  super(props);
  this.state = {editorState: EditorState.createEmpty()};
  this.onChange = (editorState) => this.setState({editorState});
}
render() {
  return (
      <Editor editorState={this.state.editorState} onChange={this.onChange} />
  );
}
...
```



# <a name="apidoc.module.draft-js.SelectionState.prototype"></a>[module draft-js.SelectionState.prototype](#apidoc.module.draft-js.SelectionState.prototype)

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getAnchorKey"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getAnchorKey ()](#apidoc.element.draft-js.SelectionState.prototype.getAnchorKey)
- description and source-code
```javascript
function getAnchorKey() {
  return this.get('anchorKey');
}
```
- example usage
```shell
...
var SecondaryClipboard = {
  cut: function cut(editorState) {
    var content = editorState.getCurrentContent();
    var selection = editorState.getSelection();
    var targetRange = null;

    if (selection.isCollapsed()) {
var anchorKey = selection.getAnchorKey();
var blockEnd = content.getBlockForKey(anchorKey).getLength();

if (blockEnd === selection.getAnchorOffset()) {
  return editorState;
}

targetRange = selection.set('focusOffset', blockEnd);
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getAnchorOffset"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getAnchorOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getAnchorOffset)
- description and source-code
```javascript
function getAnchorOffset() {
  return this.get('anchorOffset');
}
```
- example usage
```shell
...
var selection = editorState.getSelection();
var targetRange = null;

if (selection.isCollapsed()) {
  var anchorKey = selection.getAnchorKey();
  var blockEnd = content.getBlockForKey(anchorKey).getLength();

  if (blockEnd === selection.getAnchorOffset()) {
    return editorState;
  }

  targetRange = selection.set('focusOffset', blockEnd);
} else {
  targetRange = selection;
}
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getEndKey"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getEndKey ()](#apidoc.element.draft-js.SelectionState.prototype.getEndKey)
- description and source-code
```javascript
function getEndKey() {
  return this.getIsBackward() ? this.getAnchorKey() : this.getFocusKey();
}
```
- example usage
```shell
...
}
};

function modifyInlineStyle(contentState, selectionState, inlineStyle, addOrRemove) {
var blockMap = contentState.getBlockMap();
var startKey = selectionState.getStartKey();
var startOffset = selectionState.getStartOffset();
var endKey = selectionState.getEndKey();
var endOffset = selectionState.getEndOffset();

var newBlocks = blockMap.skipUntil(function (_, k) {
  return k === startKey;
}).takeUntil(function (_, k) {
  return k === endKey;
}).concat(Map([[endKey, blockMap.get(endKey)]])).map(function (block, blockKey) {
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getEndOffset"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getEndOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getEndOffset)
- description and source-code
```javascript
function getEndOffset() {
  return this.getIsBackward() ? this.getAnchorOffset() : this.getFocusOffset();
}
```
- example usage
```shell
...
};

function modifyInlineStyle(contentState, selectionState, inlineStyle, addOrRemove) {
var blockMap = contentState.getBlockMap();
var startKey = selectionState.getStartKey();
var startOffset = selectionState.getStartOffset();
var endKey = selectionState.getEndKey();
var endOffset = selectionState.getEndOffset();

var newBlocks = blockMap.skipUntil(function (_, k) {
  return k === startKey;
}).takeUntil(function (_, k) {
  return k === endKey;
}).concat(Map([[endKey, blockMap.get(endKey)]])).map(function (block, blockKey) {
  var sliceStart;
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getFocusKey"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getFocusKey ()](#apidoc.element.draft-js.SelectionState.prototype.getFocusKey)
- description and source-code
```javascript
function getFocusKey() {
  return this.get('focusKey');
}
```
- example usage
```shell
...

var anchorLeafStart = anchorLeaf.get('start');
var focusLeafStart = focusLeaf.get('start');

var anchorBlockOffset = anchorLeaf ? anchorLeafStart + anchorOffset : null;
var focusBlockOffset = focusLeaf ? focusLeafStart + focusOffset : null;

var areEqual = selection.getAnchorKey() === anchorBlockKey && selection.getAnchorOffset() === anchorBlockOffset && selection.getFocusKey
() === focusBlockKey && selection.getFocusOffset() === focusBlockOffset;

if (areEqual) {
  return selection;
}

var isBackward = false;
if (anchorBlockKey === focusBlockKey) {
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getFocusOffset"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getFocusOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getFocusOffset)
- description and source-code
```javascript
function getFocusOffset() {
  return this.get('focusOffset');
}
```
- example usage
```shell
...

var anchorLeafStart = anchorLeaf.get('start');
var focusLeafStart = focusLeaf.get('start');

var anchorBlockOffset = anchorLeaf ? anchorLeafStart + anchorOffset : null;
var focusBlockOffset = focusLeaf ? focusLeafStart + focusOffset : null;

var areEqual = selection.getAnchorKey() === anchorBlockKey && selection.getAnchorOffset() === anchorBlockOffset && selection.getFocusKey
() === focusBlockKey && selection.getFocusOffset() === focusBlockOffset;

if (areEqual) {
  return selection;
}

var isBackward = false;
if (anchorBlockKey === focusBlockKey) {
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getHasFocus"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getHasFocus ()](#apidoc.element.draft-js.SelectionState.prototype.getHasFocus)
- description and source-code
```javascript
function getHasFocus() {
  return this.get('hasFocus');
}
```
- example usage
```shell
...
var nextDirectionMap = nextEditorState.getDirectionMap();

// Text direction has changed for one or more blocks. We must re-render.
if (prevDirectionMap !== nextDirectionMap) {
  return true;
}

var didHaveFocus = prevEditorState.getSelection().getHasFocus();
var nowHasFocus = nextEditorState.getSelection().getHasFocus();

if (didHaveFocus !== nowHasFocus) {
  return true;
}

var nextNativeContent = nextEditorState.getNativelyRenderedContent();
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getIsBackward"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getIsBackward ()](#apidoc.element.draft-js.SelectionState.prototype.getIsBackward)
- description and source-code
```javascript
function getIsBackward() {
  return this.get('isBackward');
}
```
- example usage
```shell
...
}

var selection = global.getSelection();
var anchorKey = selectionState.getAnchorKey();
var anchorOffset = selectionState.getAnchorOffset();
var focusKey = selectionState.getFocusKey();
var focusOffset = selectionState.getFocusOffset();
var isBackward = selectionState.getIsBackward();

// IE doesn't support backward selection. Swap key/offset pairs.
if (!selection.extend && isBackward) {
  var tempKey = anchorKey;
  var tempOffset = anchorOffset;
  anchorKey = focusKey;
  anchorOffset = focusOffset;
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getStartKey"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getStartKey ()](#apidoc.element.draft-js.SelectionState.prototype.getStartKey)
- description and source-code
```javascript
function getStartKey() {
  return this.getIsBackward() ? this.getFocusKey() : this.getAnchorKey();
}
```
- example usage
```shell
...
remove: function remove(contentState, selectionState, inlineStyle) {
  return modifyInlineStyle(contentState, selectionState, inlineStyle, false);
}
};

function modifyInlineStyle(contentState, selectionState, inlineStyle, addOrRemove) {
var blockMap = contentState.getBlockMap();
var startKey = selectionState.getStartKey();
var startOffset = selectionState.getStartOffset();
var endKey = selectionState.getEndKey();
var endOffset = selectionState.getEndOffset();

var newBlocks = blockMap.skipUntil(function (_, k) {
  return k === startKey;
}).takeUntil(function (_, k) {
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.getStartOffset"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>getStartOffset ()](#apidoc.element.draft-js.SelectionState.prototype.getStartOffset)
- description and source-code
```javascript
function getStartOffset() {
  return this.getIsBackward() ? this.getFocusOffset() : this.getAnchorOffset();
}
```
- example usage
```shell
...
  return modifyInlineStyle(contentState, selectionState, inlineStyle, false);
}
};

function modifyInlineStyle(contentState, selectionState, inlineStyle, addOrRemove) {
var blockMap = contentState.getBlockMap();
var startKey = selectionState.getStartKey();
var startOffset = selectionState.getStartOffset();
var endKey = selectionState.getEndKey();
var endOffset = selectionState.getEndOffset();

var newBlocks = blockMap.skipUntil(function (_, k) {
  return k === startKey;
}).takeUntil(function (_, k) {
  return k === endKey;
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.hasEdgeWithin"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>hasEdgeWithin (blockKey, start, end)](#apidoc.element.draft-js.SelectionState.prototype.hasEdgeWithin)
- description and source-code
```javascript
function hasEdgeWithin(blockKey, start, end) {
  var anchorKey = this.getAnchorKey();
  var focusKey = this.getFocusKey();

  if (anchorKey === focusKey && anchorKey === blockKey) {
    var selectionStart = this.getStartOffset();
    var selectionEnd = this.getEndOffset();
    return start <= selectionEnd && selectionStart <= end;
  }

  if (blockKey !== anchorKey && blockKey !== focusKey) {
    return false;
  }

  var offsetToCheck = blockKey === anchorKey ? this.getAnchorOffset() : this.getFocusOffset();

  return start <= offsetToCheck && end >= offsetToCheck;
}
```
- example usage
```shell
...

var _props = this.props;
var blockKey = _props.blockKey;
var start = _props.start;
var text = _props.text;

var end = start + text.length;
if (!selection.hasEdgeWithin(blockKey, start, end)) {
  return;
}

// Determine the appropriate target node for selection. If the child
// is not a text node, it is a <br /> spacer. In this case, use the
// <span> itself as the selection target.
var node = ReactDOM.findDOMNode(this);
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.isCollapsed"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>isCollapsed ()](#apidoc.element.draft-js.SelectionState.prototype.isCollapsed)
- description and source-code
```javascript
function isCollapsed() {
  return this.getAnchorKey() === this.getFocusKey() && this.getAnchorOffset() === this.getFocusOffset();
}
```
- example usage
```shell
...
 */
var SecondaryClipboard = {
  cut: function cut(editorState) {
    var content = editorState.getCurrentContent();
    var selection = editorState.getSelection();
    var targetRange = null;

    if (selection.isCollapsed()) {
var anchorKey = selection.getAnchorKey();
var blockEnd = content.getBlockForKey(anchorKey).getLength();

if (blockEnd === selection.getAnchorOffset()) {
  return editorState;
}
...
```

#### <a name="apidoc.element.draft-js.SelectionState.prototype.serialize"></a>[function <span class="apidocSignatureSpan">draft-js.SelectionState.prototype.</span>serialize ()](#apidoc.element.draft-js.SelectionState.prototype.serialize)
- description and source-code
```javascript
function serialize() {
  return 'Anchor: ' + this.getAnchorKey() + ':' + this.getAnchorOffset() + ', ' + 'Focus: ' + this.getFocusKey() + ':' + this.getFocusOffset
() + ', ' + 'Is Backward: ' + String(this.getIsBackward()) + ', ' + 'Has Focus: ' + String(this.getHasFocus());
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
