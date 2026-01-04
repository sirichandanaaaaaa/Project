import { useEffect } from 'react';
import { useNavigate, Link } from 'react-router-dom';
import { useAuth } from '@/hooks/useAuth';
import { Button } from '@/components/ui/button';
import { BookOpen, ArrowRight, CheckCircle, Loader2 } from 'lucide-react';

const Index = () => {
  const navigate = useNavigate();
  const { user, loading } = useAuth();

  useEffect(() => {
    if (user && !loading) {
      navigate('/dashboard');
    }
  }, [user, loading, navigate]);

  if (loading) {
    return (
      <div className="flex min-h-screen items-center justify-center bg-background">
        <Loader2 className="h-8 w-8 animate-spin text-primary" />
      </div>
    );
  }

  const features = [
    'Create and manage courses easily',
    'Track course information',
    'Secure user authentication',
    'Fast and responsive interface',
  ];

  return (
    <div className="min-h-screen bg-gradient-to-br from-background via-background to-muted">
      {/* Header */}
      <header className="container mx-auto px-4 py-6 flex items-center justify-between">
        <div className="flex items-center gap-2 text-primary">
          <BookOpen className="h-8 w-8" />
          <span className="text-2xl font-bold">CourseHub</span>
        </div>
        <div className="flex gap-4">
          <Link to="/auth">
            <Button variant="outline">Login</Button>
          </Link>
          <Link to="/auth">
            <Button>Get Started</Button>
          </Link>
        </div>
      </header>

      {/* Hero Section */}
      <main className="container mx-auto px-4 py-16 md:py-24">
        <div className="max-w-3xl mx-auto text-center">
          <h1 className="text-4xl md:text-6xl font-bold text-foreground mb-6">
            Manage Your Courses
            <span className="text-primary block mt-2">With Ease</span>
          </h1>
          <p className="text-xl text-muted-foreground mb-8 max-w-2xl mx-auto">
            A simple and powerful course management application. Create, organize, and track all your courses in one place.
          </p>
          <Link to="/auth">
            <Button size="lg" className="text-lg px-8 py-6">
              Start Managing Courses
              <ArrowRight className="ml-2 h-5 w-5" />
            </Button>
          </Link>
        </div>

        {/* Features */}
        <div className="mt-20 max-w-2xl mx-auto">
          <h2 className="text-2xl font-semibold text-center text-foreground mb-8">
            Everything you need
          </h2>
          <div className="grid gap-4 md:grid-cols-2">
            {features.map((feature, index) => (
              <div
                key={index}
                className="flex items-center gap-3 p-4 rounded-lg bg-card border"
              >
                <CheckCircle className="h-5 w-5 text-primary flex-shrink-0" />
                <span className="text-foreground">{feature}</span>
              </div>
            ))}
          </div>
        </div>
      </main>

      {/* Footer */}
      <footer className="container mx-auto px-4 py-8 mt-auto">
        <div className="text-center text-muted-foreground text-sm">
          <p>© 2024 CourseHub. Course Management Application.</p>
        </div>
      </footer>
    </div>
  );
};

export default Index;
