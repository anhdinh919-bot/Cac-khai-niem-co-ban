# Cac-khai-niem-co-ban
\section{Phần 1: Các khái niệm cơ bản về Hàm số Lượng giác}

\subsection{Mục tiêu phần học}
Sau khi hoàn thành phần này, người học có thể:
\begin{itemize}
    \item \textbf{Nắm vững lý thuyết nền tảng:} Hiểu rõ định nghĩa và sự hình thành của các hàm số lượng giác cơ bản $y = \sin x$, $y = \cos x$, $y = \tan x$ và $y = \cot x$ từ đường tròn đơn vị.
    \item \textbf{Hiểu rõ đặc trưng đồ thị:} Nhận biết tính tuần hoàn và hình dáng "hình sin" đặc trưng của đồ thị.
    \item \textbf{Khai thác các tính chất quan trọng:} Xác định chính xác chu kỳ, tập giá trị và các điểm cực trị (Max/Min) làm cơ sở toán học vững chắc để mô hình hóa các hiện tượng thực tế.
\end{itemize}
\vspace{0.5cm}

Trong giải tích, nếu đa thức (như hàm bậc 2, bậc 4) thường được dùng để mô tả sự tăng trưởng hay quỹ đạo ném, thì hàm số lượng giác lại là công cụ tối ưu và duy nhất để mô phỏng sự tuần hoàn. Bất chấp hệ số biên độ hay tần số thay đổi ra sao, đồ thị của chúng luôn giữ vững những cấu trúc nhịp nhàng, lặp đi lặp lại một cách hoàn hảo qua thời gian.

% ============================================================

\subsection{Định nghĩa và Dạng tổng quát}
Hàm số lượng giác biểu diễn mối quan hệ giữa một góc (đo bằng radian) và tọa độ của một điểm di chuyển trên đường tròn lượng giác đơn vị. Trong các ứng dụng thực tế (như sóng âm, dao động cơ điều hòa), hàm lượng giác thường xuất hiện dưới dạng tổng quát:
\[ y = A \sin(\omega x + \varphi) + B \quad (A \neq 0, \omega \neq 0) \]

\textbf{Ví dụ 1 (Ví dụ về hàm lượng giác):}
Các hàm số sau đây là hàm lượng giác:
\begin{itemize}
    \item $y = 3\sin(2x + \pi)$ (Mô tả sóng với biên độ bằng $3$).
    \item $y = 5\cos^2 x - 1$.
\end{itemize}

\textbf{Ví dụ 2 (Ví dụ KHÔNG phải hàm lượng giác thuần túy):}
\begin{itemize}
    \item $y = x^2 + \sin x$ (Đây là hàm hỗn hợp giữa đa thức và lượng giác).
    \item $y = \sin(x^2 + 1)$ (Hàm hợp có chứa biến bậc hai bên trong).
\end{itemize}

% ============================================================

\subsection{Tập xác định và Tính tuần hoàn}
Tính chất hình học nổi bật nhất của hàm lượng giác là sự lặp lại (tuần hoàn):
\begin{itemize}
    \item \textbf{Hàm $y = \sin x$ và $y = \cos x$:} Tập xác định $D = \mathbb{R}$. Đây là các hàm tuần hoàn với chu kỳ cơ sở $T = 2\pi$. Nghĩa là cứ sau một khoảng $2\pi$, đồ thị lại lặp lại hình dáng ban đầu: $\sin(x + 2\pi) = \sin x$.
    \item \textbf{Hàm $y = \tan x$:} Tập xác định $D = \mathbb{R} \setminus \left\lbrace \frac{\pi}{2} + k\pi \mid k \in \mathbb{Z} \right\rbrace$, chu kỳ lặp lại ngắn hơn, $T = \pi$.
\end{itemize}

% ============================================================

\subsection{Cực trị và Sự biến thiên}
Không giống như hàm đa thức có thể tiến tới $+\infty$ hoặc $-\infty$, hàm $y = \sin x$ và $y = \cos x$ luôn bị giới hạn ngặt nghèo trong một khoảng cố định (tập giá trị $[-1, 1]$):
\[ -1 \leq \sin x \leq 1 \quad \text{và} \quad -1 \leq \cos x \leq 1 \]

\begin{itemize}
    \item \textbf{Điểm cực đại (Đỉnh sóng):} Hàm $y = \sin x$ đạt cực đại bằng $1$ tại các điểm $x = \frac{\pi}{2} + k2\pi$ $(k \in \mathbb{Z})$.
    \item \textbf{Điểm cực tiểu (Đáy sóng):} Hàm $y = \sin x$ đạt cực tiểu bằng $-1$ tại các điểm $x = -\frac{\pi}{2} + k2\pi$ $(k \in \mathbb{Z})$.
\end{itemize}

\vspace{0.5cm}
\begin{center}
\begin{tcolorbox}[colback=blue!5!white,colframe=blue!75!black,title=\textbf{Mẹo nhớ nhanh đồ thị cơ bản}]
\begin{itemize}
    \item \textbf{Biên độ (Max/Min):} Đồ thị $\sin$ và $\cos$ cơ bản luôn dao động như một "làn sóng" bị nhốt giữa hai đường thẳng song song $y = 1$ và $y = -1$.
    \item \textbf{Điểm xuất phát:} Hàm $\sin x$ luôn đi qua gốc tọa độ $(0;0)$ (bắt đầu từ mức cân bằng), trong khi hàm $\cos x$ xuất phát từ "đỉnh sóng" $(0;1)$.
\end{itemize}
\end{tcolorbox}
\end{center}
