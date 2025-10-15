## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->





namespace WinFormsApp3
{
    partial class Form1
    {
        /// <summary>
        ///  Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        ///  Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        ///  Required method for Designer support - do not modify
        ///  the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            this.tableLayoutPanel1 = new System.Windows.Forms.TableLayoutPanel();
            this.currentPlayerlable = new System.Windows.Forms.Label();

            this.button1 = new System.Windows.Forms.Button();
            this.button2 = new System.Windows.Forms.Button();
            this.button3 = new System.Windows.Forms.Button();
            this.button4 = new System.Windows.Forms.Button();
            this.button5 = new System.Windows.Forms.Button();
            this.button6 = new System.Windows.Forms.Button();
            this.button7 = new System.Windows.Forms.Button();
            this.button8 = new System.Windows.Forms.Button();
            this.button9 = new System.Windows.Forms.Button();

            this.SuspendLayout();

            this.tableLayoutPanel1.ColumnCount = 3;
            this.tableLayoutPanel1.RowCount = 3;
            this.tableLayoutPanel1.Location = new System.Drawing.Point(50, 50);
            this.tableLayoutPanel1.Name = "tableLayoutPanel1";
            this.tableLayoutPanel1.Size = new System.Drawing.Size(510, 330);
            this.tableLayoutPanel1.TabIndex = 0;

            this.tableLayoutPanel1.ColumnStyles.Add(new System.Windows.Forms.ColumnStyle(System.Windows.Forms.SizeType.Percent, 33.33F));
            this.tableLayoutPanel1.ColumnStyles.Add(new System.Windows.Forms.ColumnStyle(System.Windows.Forms.SizeType.Percent, 33.33F));
            this.tableLayoutPanel1.ColumnStyles.Add(new System.Windows.Forms.ColumnStyle(System.Windows.Forms.SizeType.Percent, 33.33F));

            this.tableLayoutPanel1.RowStyles.Add(new System.Windows.Forms.RowStyle(System.Windows.Forms.SizeType.Percent, 33.33F));
            this.tableLayoutPanel1.RowStyles.Add(new System.Windows.Forms.RowStyle(System.Windows.Forms.SizeType.Percent, 33.33F));
            this.tableLayoutPanel1.RowStyles.Add(new System.Windows.Forms.RowStyle(System.Windows.Forms.SizeType.Percent, 33.33F));

            this.button1.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button1.Name = "button1";
            this.button1.TabIndex = 1;
            this.button1.Text = "";
            this.button1.UseVisualStyleBackColor = true;
            this.button1.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button1, 0, 0);

            this.button2.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button2.Name = "button2";
            this.button2.TabIndex = 2;
            this.button2.Text = "";
            this.button2.UseVisualStyleBackColor = true;
            this.button2.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button2, 1, 0);

            this.button3.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button3.Name = "button3";
            this.button3.TabIndex = 3;
            this.button3.Text = "";
            this.button3.UseVisualStyleBackColor = true;
            this.button3.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button3, 2, 0);

            this.button4.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button4.Name = "button4";
            this.button4.TabIndex = 4;
            this.button4.Text = "";
            this.button4.UseVisualStyleBackColor = true;
            this.button4.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button4, 0, 1);
            this.button5.Dock = System.Windows.Forms.DockStyle.Fill;

            this.button5.Name = "button5";
            this.button5.TabIndex = 5;
            this.button5.Text = "";
            this.button5.UseVisualStyleBackColor = true;
            this.button5.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button5, 1, 1);

            this.button6.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button6.Name = "button6";
            this.button6.TabIndex = 6;
            this.button6.Text = "";
            this.button6.UseVisualStyleBackColor = true;
            this.button6.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button6, 2, 1);

            this.button7.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button7.Name = "button7";
            this.button7.TabIndex = 7;
            this.button7.Text = "";
            this.button7.UseVisualStyleBackColor = true;
            this.button7.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button7, 0, 2);

            this.button8.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button8.Name = "button8";
            this.button8.TabIndex = 8;
            this.button8.Text = "";
            this.button8.UseVisualStyleBackColor = true;
            this.button8.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button8, 1, 2);

            this.button9.Dock = System.Windows.Forms.DockStyle.Fill;
            this.button9.Name = "button9";
            this.button9.TabIndex = 9;
            this.button9.Text = "";
            this.button9.UseVisualStyleBackColor = true;
            this.button9.Click += this.button_Click;
            this.tableLayoutPanel1.Controls.Add(this.button9, 2, 2);

            this.currentPlayerlable.AutoSize = true;
            this.currentPlayerlable.Location = new System.Drawing.Point(50, 10);
            this.currentPlayerlable.Name = "currentPlayerlable";
            this.currentPlayerlable.Size = new System.Drawing.Size(150, 20);
            this.currentPlayerlable.TabIndex = 10;
            this.currentPlayerlable.Text = "Teraz Gra: X";

            this.AutoScaleDimensions = new System.Drawing.SizeF(7F, 15F);
            this.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font;
            this.ClientSize = new System.Drawing.Size(620, 400);
            this.Controls.Add(this.currentPlayerlable);
            this.Controls.Add(this.tableLayoutPanel1);
            this.Name = "Form1";
            this.Text = "Tic Tac Toe";
            this.ResumeLayout(false);
            this.PerformLayout();
        }

        #endregion

        private System.Windows.Forms.TableLayoutPanel tableLayoutPanel1;
        private System.Windows.Forms.Label currentPlayerlable;

        private System.Windows.Forms.Button button1;
        private System.Windows.Forms.Button button2;
        private System.Windows.Forms.Button button3;
        private System.Windows.Forms.Button button4;
        private System.Windows.Forms.Button button5;
        private System.Windows.Forms.Button button6;
        private System.Windows.Forms.Button button7;
        private System.Windows.Forms.Button button8;
        private System.Windows.Forms.Button button9;
    }
}
