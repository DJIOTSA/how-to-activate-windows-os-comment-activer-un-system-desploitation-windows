# How to Activate Windows in 3 Steps / Comment activer Windows en 3 étapes

Follow these simple steps to activate your Windows operating system:

Suivez ces étapes simples pour activer votre système d'exploitation Windows :

## Step 1: Open Command Line Interface (CLI) as Administrator / Étape 1 : Ouvrir l'interface en ligne de commande (CLI) en tant qu'administrateur

- Press `Win + X` on your keyboard or right-click the Start button.
- Sélectionnez **Invite de commandes (Admin)** ou **Windows PowerShell (Admin)** dans le menu.
- If prompted by User Account Control (UAC), click **Yes** to allow the app to make changes.
- Si une notification du contrôle de compte utilisateur (UAC) apparaît, cliquez sur **Oui** pour permettre à l'application d'apporter des modifications.

## Step 2: Set the KMS Server / Étape 2 : Configurer le serveur KMS

- In the Command Prompt window, type the following command and press **Enter**:
- Dans la fenêtre d'invite de commande, tapez la commande suivante et appuyez sur **Entrée** :

    ```
    slmgr /skms kms8.msguides.com
    ```

- After running this command, a dialog box will appear. Click **OK** when done.
- Après avoir exécuté cette commande, une boîte de dialogue apparaîtra. Cliquez sur **OK** une fois terminé.

## Step 3: Activate Windows / Étape 3 : Activer Windows

- Next, type the following command and press **Enter**:
- Ensuite, tapez la commande suivante et appuyez sur **Entrée** :

    ```
    slmgr /ato
    ```

- Again, a dialog box will appear. Click **OK** when done.
- Une fois encore, une boîte de dialogue apparaîtra. Cliquez sur **OK** une fois terminé.

Your Windows should now be activated. If you encounter any issues, try restarting your computer and repeating these steps.

Votre Windows devrait maintenant être activé. Si vous rencontrez des problèmes, essayez de redémarrer votre ordinateur et de répéter ces étapes.
